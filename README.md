# psbettercodequaleslint
##2. Setting up ESLint in Your Project
###2 Installing and Running ESLint
```
{
  env:{
    browser: true
  },
  extends: eslint:recommended,
  rules:{
    "no-console":"error",
    "indent":[
      error,
      4
    ],
    "linebreak-style":[
      error,
      unix
    ],
    "quotes":[
      error,
      single
    ],
    "semi":[
      error,
      always
    ]
  }
}
```

###5 Git Hooks
```
npm install --save-dev pre-commit
```
in package.json
```
scripts:{
  test: eslint public/js && mocha test
},
"pre-commit":["test"]
```


##5. Common ESLint Use Cases
###2 Linting Client and Server JavaScript
by default eslint use .eslintrc.json file in root folder, we can create another file in public folder
```
/public/js/.eslintrc.json
```




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

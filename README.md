# :clap: Ella's Bootstrap Theme Kit v1.1.0 :clap:

<!-- 
![Bootstrap](https://img.shields.io/badge/bootstrap%20-b98aff.svg?&style=for-the-badge&logo=bootstrap&logoColor=white)
![SASS](https://img.shields.io/badge/SASS%20-hotpink.svg?&style=for-the-badge&logo=SASS&logoColor=white)
![jQuery](https://img.shields.io/badge/jquery%20-%230769AD.svg?&style=for-the-badge&logo=jquery&logoColor=white)
![NodeJS](https://img.shields.io/badge/node.js%20-70BC4F.svg?&style=for-the-badge&logo=node.js&logoColor=white)
-->

![Bootstrap](https://img.shields.io/badge/bootstrap%20-v4.6-b98aff.svg?&style=flat-square&logo=bootstrap&logoColor=white)
![SASS](https://img.shields.io/badge/SASS-v5.0.0-hotpink.svg?&style=flat-square&logo=SASS&logoColor=white)
![jQuery](https://img.shields.io/badge/jquery%20-v3.5.1-%230769AD.svg?&style=flat-square&logo=jquery&logoColor=white)
![NodeJS](https://img.shields.io/badge/node.js%20-v14.15.1-70BC4F.svg?&style=flat-square&logo=node.js&logoColor=white)

## 3 Step Usage :+1:

1. setup color-system and breakpoint for your project in scss/main/_theme.scss

2. open terminal and run ``npm run run-all``

3. Let's CODEEEEE !!!!! :fire: :fire:


--- 
 
## What extend from pure bootstrap 4.6
#### 1. More responsive things !!!
  - responsive width size have already done :heart_eyes:
  
    - w-xxl-100, 75, 50, 25
    - w-xl-100
    - w-lg-100
    - w-md-100
    - w-sm-100
    - w-xsm-100
    
    ============
    
    - h-xxl-100, 75, 50, 25
    - h-xl-100
    - h-lg-100
    - h-md-100
    - h-sm-100
    - h-xsm-100
        
    =============
    
    - mw-xl-100
    - mh-xl-100
    
     ============
  
  - responsive viewport sizing
    
    - vw-xxl-100, 75, 50, 25
    - vw-xl-100
    - vw-lg-100
    - vw-md-100
    - vw-sm-100
    - vw-xsm-100
    
     ============
    
    - vh-xxl-100, 75, 50, 25 
    - vh-xl-100
    - vh-lg-100
    - vh-md-100
    - vh-sm-100
    - vh-xsm-100      

#### 2. More responsive size
  - xsm >= 375px
  - xxl >= 1400px

#### 3. mixin
    - mq: media query
    - placeholder: modify input's placeholder

#### 4. Borrow from Bootstrap 5
    - lh-xsm
    - lh-sm
    - lh-md
    - lh-lg
    - lh-xl
    - lh-xxl

    - fw-thin
    - fw-lighter
    - fw-light
    - fw-normal
    - fw-medium
    - fw-semi-bold
    - fw-bold
    - fw-bolder
    - fw-black

    - fs-10, ..., 70
    - fs-xxl-10, 11, 12, ..., 70
    - fs-xl-10
    - fs-lg-10
    - fs-md-10
    - fs-sm-10
    - fs-xsm-10

#### 5. More color system :rainbow: :rainbow: :rainbow: 

## Included

### files
```
ella-bootstrap-theme-kit/
│   
├── scss/
│   ├── bootstrap-4/
|   |    └── scss/
|   |          └── bootstrap.scss
|   |
│   ├── main/
|   |    ├── _theme.scss (*dynamic)
|   |    ├── 404.scss
|   |    └── index.scss
|   |         
│   └── my_scss_template/
|        ├── _color.scss
|        ├── _mixin.scss
|        ├── _sizing.scss
|        ├── _text.scss
|        ├── _util.scss
|        └── template.scss
|              
├── view/
│   ├── components/
|   |     ├── footer.pug
|   |     └── navbar.pug
|   |
│   ├── layout/
|   |     ├── base-layout.pug 
|   |     └── main-layout.pug (*dynamic)
|   |
|   ├── sub-pages/
|   |
|   ├── 404.pug
|   ├── error.pug
|   └── index.pug
|
└── package.json
```

### build in set up
  - Bootstrap v4.6 with jQuery
  - SASS template
  - script for run build in package.json
  - project structure
  - routes for page 404 not found
  - owl carousel

---
last edit : 14/02/2021

#### previous version
##### v1.0.0
  - add 

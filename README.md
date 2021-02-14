# :clap: Ella's Bootstrap Theme Kit V 1.1.0 :clap:
 
## What's extend from pure bootstrap 4.6
#### 1. More responsive things !!!

--- 
# :clap: Ella's Bootstrap Theme Kit V 1.0.0 :clap: 
 
## What's extend from pure bootstrap 4.6
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
    
  - responsive font size
    
    - fs-1, ..., 9
    - fs-xxl-1, 2, 3, ..., 9
    - fs-xl-1
    - fs-lg-1
    - fs-md-1
    - fs-sm-1
    - fs-xsm-1
    
     ============

    - fs-10, ..., 70
    - fs-xxl-10, 11, 12, ..., 70
    - fs-xl-10
    - fs-lg-10
    - fs-md-10
    - fs-sm-10
    - fs-xsm-10
  
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

#### 3. More color system :rainbow: :rainbow: :rainbow: 

#### 4. Easier button create

#### 5. mixin
    - mq: media query
    - placeholder: modify input's placeholder

#### 6. Can use some utility things from Bootstrap 5 syntax
    - fs-#{$value} : font-size
    - fw-#{$value} : font-weight
    - lh-#{$value} : line-hight

    - border width size is available
    
### other
1. script npm run for build all template

2. simple source setup

## Files included

```
ella-bootstrap-theme-kit/
│   
├── scss/
│   ├── bootstrap-4/
|   |    └── scss/
|   |          └── bootstrap.scss
|   |
│   ├── main/
|   |    ├── _theme.scss
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
│   ├── index.pug
│   ├── error.pug
│   └── layout/
|         └── layout.pug
|
└── package.json
```

## 3 Step Usage :+1:

1. setup color-system and breakpoint for your project in scss/main/_theme.scss

2. open terminal and run ``npm run run all``

3. Let's CODEEEEE !!!!! :fire: :fire:

---

last edit 07/02/2021

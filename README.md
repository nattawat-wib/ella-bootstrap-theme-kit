# :clap: Ella's Bootstrap Theme Kit v1.1.0 :clap:

![Bootstrap](https://img.shields.io/badge/bootstrap%20-b98aff.svg?&style=for-the-badge&logo=bootstrap&logoColor=white)
![SASS](https://img.shields.io/badge/SASS%20-hotpink.svg?&style=for-the-badge&logo=SASS&logoColor=white)
![jQuery](https://img.shields.io/badge/jquery%20-%230769AD.svg?&style=for-the-badge&logo=jquery&logoColor=white)
![NodeJS](https://img.shields.io/badge/node.js%20-70BC4F.svg?&style=for-the-badge&logo=node.js&logoColor=white)


![Bootstrap](https://img.shields.io/badge/bootstrap%20-v4.6-b98aff.svg?&style=flat-square&logo=bootstrap&logoColor=white)
![SASS](https://img.shields.io/badge/SASS-v5.0.0-hotpink.svg?&style=flat-square&logo=SASS&logoColor=white)
![jQuery](https://img.shields.io/badge/jquery%20-v3.5.1-%230769AD.svg?&style=flat-square&logo=jquery&logoColor=white)
![NodeJS](https://img.shields.io/badge/node.js%20-v14.15.1-70BC4F.svg?&style=flat-square&logo=node.js&logoColor=white)

## 3 Step Usage :+1:

1. setup color-system and breakpoint for your project in scss/main/_theme.scss

2. open terminal and run ``npm run run-all``

3. Let's CODEEEEE !!!!! :fire: :fire:


--- 
 
## What extend from vanilla bootstrap 4.6


### 1. More responsive size
  | Class | Dimension |
  | ----- | :-------- |
  | -     | > 0px     |
  | xsm * | ≥ 375px   |
  | sm    | ≥ 576px   |
  | md    | ≥ 768px   |
  | lg    | ≥ 992px   |
  | xl    | ≥ 1200px  |
  | xxl   | ≥ 1400px  |

   > NOTE:
   > * special for Iphone5 / SE responsive


### 2. More responsive things !!!
  

   ####  Width responsive
  | -     | xsm       | sm       | md       | lg       | xl       | xxl       | Width |
  | ----- | --------- | -------- | -------- | -------- | -------- | --------- | :---: |
  | w-25  | w-xsm-25  | w-sm-25  | w-md-25  | w-lg-25  | w-xl-25  | w-xxl-25  |  25%  |
  | w-50  | w-xsm-50  | w-sm-50  | w-md-50  | w-lg-50  | w-xl-50  | w-xxl-50  |  50%  |
  | w-75  | w-xsm-75  | w-sm-75  | w-md-75  | w-lg-75  | w-xl-75  | w-xxl-75  |  75%  |
  | w-100 | w-xsm-100 | w-sm-100 | w-md-100 | w-lg-100 | w-xl-100 | w-xxl-100 | 100%  |

   #### Height responsive
  | -     | xsm       | sm       | md       | lg       | xl       | xxl       | Height |
  | ----- | --------- | -------- | -------- | -------- | -------- | --------- | :----: |
  | h-25  | h-xsm-25  | h-sm-25  | h-md-25  | h-lg-25  | h-xl-25  | h-xxl-25  |  25%   |
  | h-50  | h-xsm-50  | h-sm-50  | h-md-50  | h-lg-50  | h-xl-50  | h-xxl-50  |  50%   |
  | h-75  | h-xsm-75  | h-sm-75  | h-md-75  | h-lg-75  | h-xl-75  | h-xxl-75  |  75%   |
  | h-100 | h-xsm-100 | h-sm-100 | h-md-100 | h-lg-100 | h-xl-100 | h-xxl-100 |  100%  |


  #### Viewport width responsive
  | -      | xsm        | sm        | md        | lg        | xl        | xxl        | Viewport width |
  | ------ | ---------- | --------- | --------- | --------- | --------- | ---------- | :------------: |
  | vw-25  | vw-xsm-25  | vw-sm-25  | vw-md-25  | vw-lg-25  | vw-xl-25  | vw-xxl-25  |      25vw      |
  | vw-50  | vw-xsm-50  | vw-sm-50  | vw-md-50  | vw-lg-50  | vw-xl-50  | vw-xxl-50  |      50vw      |
  | vw-75  | vw-xsm-75  | vw-sm-75  | vw-md-75  | vw-lg-75  | vw-xl-75  | vw-xxl-75  |      75vw      |
  | vw-100 | vw-xsm-100 | vw-sm-100 | vw-md-100 | vw-lg-100 | vw-xl-100 | vw-xxl-100 |     100vw      |

  #### Viewport height responsive
  | -      | xsm        | sm        | md        | lg        | xl        | xxl        | Viewport height |
  | ------ | ---------- | --------- | --------- | --------- | --------- | ---------- | :-------------: |
  | vh-25  | vh-xsm-25  | vh-sm-25  | vh-md-25  | vh-lg-25  | vh-xl-25  | vh-xxl-25  |      25vh       |
  | vh-50  | vh-xsm-50  | vh-sm-50  | vh-md-50  | vh-lg-50  | vh-xl-50  | vh-xxl-50  |      50vh       |
  | vh-75  | vh-xsm-75  | vh-sm-75  | vh-md-75  | vh-lg-75  | vh-xl-75  | vh-xxl-75  |      75vh       |
  | vh-100 | vh-xsm-100 | vh-sm-100 | vh-md-100 | vh-lg-100 | vh-xl-100 | vh-xxl-100 |      100vh      |


### 3. mixin
   #### __@include__ mq($breakdownSize)
      Type: String
      Default: -
      for media query

   #### __@include__ placeholder()
      Type: -
      Default: -
      for modify input's placeholder

   #### __@include__ line-clamp($lineNumber)
      Type: Number
      Default: -
      for defined line clamp

### 4. Borrow from Bootstrap 5 

#### line hight & font weight
  | Class           | Line space |     | Class        | Font weight |
  | --------------- | :--------: | --- | ------------ | :---------: |
  | lh-xsm          |     1      |     | fw-thin      |     100     |
  | lh-sm           |    1.25    |     | fw-lighter   |     200     |
  | lh-md (default) |    1.5     |     | fw-light     |     300     |
  | lh-lg           |    1.75    |     | fw-normal    |     400     |
  | lh-xl           |     2      |     | fw-medium    |     500     |
  | lh-xxl          |    2.25    |     | fw-semi-bold |     600     |
  |                 |            |     | fw-semi-bold |     600     |
  |                 |            |     | fw-bold      |     700     |
  |                 |            |     | fw-bolder    |     800     |
  |                 |            |     | fw-black     |     900     |

#### Font size responsive
  | -     | xsm       | sm       | md       | lg       | xl       | xxl       | font size |
  | ----- | --------- | -------- | -------- | -------- | -------- | --------- | :-------: |
  | fs-10 | fs-xsm-10 | fs-sm-10 | fs-md-10 | fs-lg-10 | fs-xl-10 | fs-xxl-10 |   10px    |
  | fs-12 | fs-xsm-12 | fs-sm-12 | fs-md-12 | fs-lg-12 | fs-xl-12 | fs-xxl-12 |   12px    |
  | fs-14 | fs-xsm-14 | fs-sm-14 | fs-md-14 | fs-lg-14 | fs-xl-14 | fs-xxl-14 |   14px    |
  | fs-16 | fs-xsm-16 | fs-sm-16 | fs-md-16 | fs-lg-16 | fs-xl-16 | fs-xxl-16 |   16px    |
  | ...   | ...       | ...      | ...      | ...      | ...      | ...       |    ...    |
  | fs-80 | fs-xsm-80 | fs-sm-80 | fs-md-80 | fs-lg-80 | fs-xl-80 | fs-xxl-80 |   80px    |
  > NOTE: font size is available only even number 10 to 80

### 5. More color system :rainbow: :rainbow: :rainbow: 

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

## build in set up
  - Bootstrap v4.6 with jQuery
  - SASS template
  - script for run build in package.json
  - project structure
  - routes for page 404 not found
  - owl carousel

#### edited feature from previous version
  - __remove__ fs-1, ..., 9
  - __remove__ border class
  - __remove__ odd number from fs- class
  - __remove__ max width, max height responsive

  - __add__ mixin line-clamp
---
last edit : 14/02/2021

### previous version
#### v1.0.0
  - set up prototype
  - __add__ more responsive size xsm and xxl
  - __add__ sizing responsive (with, height, max width, max height, vw and vh)
  - __add__ font size class by rem (fs-1, ..., 9)
  - __add__ font size class by pixel (fs-10, 11, 12, 13, ..., 70)
  - __add__ font weight class (fw-thin, lighter, light, ..., bolder and black)
  - __add__ line height class (lh-xsm, sm, md, ..., xl, xxl)
  - __add__ border class

# Ex08 Event Registration Web Application
## Date:24/12/2025

## AIM:
To design, develop and deploy a web application for event registration using Figma UI tool.

## UI DESIGN TOOL:
Figma

## DESIGN STEPS:

### Step 1:
Use frames to represent screens or sections.

### Step 2:
Add column grids for consistent spacing and alignment.

### Step 3:
Insert shapes, text, buttons, and icons.

### Step 4:
Use Auto Layout for flexible, responsive design.

### Step 5:
Define color, text, and effect styles globally for consistency.

### Step 6:
Name layers logically and group related elements.

### Step 6:
Link frames to show navigation or interactions.

### Step 7:
Select the specific frame while generating code using Anima plugin.

## CODE:
```
index.html

1 box

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="styleguide.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone-plus">
      <img class="download" src="img/download-1.png" />
      <div class="rectangle"></div>
      <div class="div"></div>
      <div class="text-wrapper">REGISTRATION</div>
      <div class="rectangle-2"></div>
      <div class="text-wrapper-2">REGSITER</div>
      <div class="text-wrapper-3">GAMING-EVENT</div>
      <div class="rectangle-3"></div>
      <div class="text-wrapper-4">LOGIN</div>
      <img class="image" src="img/image-1.png" />
    </div>
  </body>
</html>


2 box

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="styleguide.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone">
      <img class="star" src="img/star-1.svg" />
      <img class="img" src="img/star-2.svg" />
      <div class="rectangle"></div>
      <div class="text-wrapper">FREE FIRE</div>
      <div class="div"></div>
      <div class="rectangle-2"></div>
      <div class="text-wrapper-2">CRICKET</div>
      <div class="rectangle-3"></div>
      <div class="text-wrapper-3">BAZ-BALL</div>
      <div class="rectangle-4"></div>
      <div class="text-wrapper-4">PUBG</div>
      <div class="text-wrapper-5">FOOTBALL</div>
      <img class="star-2" src="img/star-3.svg" />
      <img class="star-3" src="img/star-4.svg" />
      <div class="text-wrapper-6">HOCKEY</div>
      <img class="text-on-a-path" src="img/text-on-a-path.svg" />
    </div>
  </body>
</html>


3 box

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="styleguide.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone-plus">
      <div class="rectangle"></div>
      <div class="div"></div>
      <div class="text-wrapper">NAME:</div>
      <img class="line" src="img/line-1.svg" />
      <div class="text-wrapper-2">register no:</div>
      <img class="img" src="img/line-2.svg" />
      <div class="text-wrapper-3">Department:</div>
      <img class="line-2" src="img/line-3.svg" />
      <div class="text-wrapper-4">College Name:</div>
      <img class="line-3" src="img/line-4.svg" />
      <div class="rectangle-2"></div>
      <div class="text-wrapper-5">SUBMIT</div>
      <div class="text-wrapper-6">Have A Great</div>
      <div class="text-wrapper-7">enjoyment</div>
    </div>
  </body>
</html>


gobal.css

box 1

.iphone-plus {
  background-color: #ffffff;
  width: 100%;
  min-width: 411px;
  min-height: 700px;
  position: relative;
}

.iphone-plus .download {
  position: absolute;
  top: 0;
  left: 0;
  width: 411px;
  height: 86px;
  aspect-ratio: 5.01;
  object-fit: cover;
}

.iphone-plus .rectangle {
  position: absolute;
  top: 242px;
  left: 8px;
  width: 394px;
  height: 72px;
  background-color: #3b429e;
  border: 1px solid;
  border-color: #f60e0e;
}

.iphone-plus .div {
  position: absolute;
  top: 333px;
  left: 8px;
  width: 394px;
  height: 67px;
  background-color: #e9d134;
  border: 1px solid;
  border-color: #1b06ff;
}

.iphone-plus .text-wrapper {
  position: absolute;
  top: 350px;
  left: 46px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #ff0c10;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone-plus .rectangle-2 {
  position: absolute;
  top: 452px;
  left: 74px;
  width: 259px;
  height: 66px;
  background-color: #54b39a;
}

.iphone-plus .text-wrapper-2 {
  position: absolute;
  top: 460px;
  left: 108px;
  -webkit-text-stroke: 1px #a919bc;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone-plus .text-wrapper-3 {
  position: absolute;
  top: 260px;
  left: 52px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #39d951;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone-plus .rectangle-3 {
  position: absolute;
  top: 564px;
  left: 73px;
  width: 261px;
  height: 73px;
  background-color: #191818;
  border: 1px solid;
  border-color: #f10e0e;
}

.iphone-plus .text-wrapper-4 {
  position: absolute;
  top: 577px;
  left: 129px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #f81414;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone-plus .image {
  position: absolute;
  top: 86px;
  left: 129px;
  width: 146px;
  height: 140px;
  aspect-ratio: 1.04;
  object-fit: cover;
}

box 2

.iphone {
  background-color: #ffffff;
  overflow: hidden;
  width: 100%;
  min-width: 415px;
  min-height: 700px;
  position: relative;
}

.iphone .star {
  position: absolute;
  top: 12px;
  left: 2px;
  width: 59px;
  height: 47px;
}

.iphone .img {
  position: absolute;
  top: 12px;
  left: 351px;
  width: 49px;
  height: 47px;
}

.iphone .rectangle {
  top: 94px;
  height: 63px;
  background-color: #360efd;
  position: absolute;
  left: 20px;
  width: 373px;
}

.iphone .text-wrapper {
  position: absolute;
  top: 102px;
  left: 78px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone .div {
  top: 202px;
  height: 63px;
  background-color: #46ad36;
  position: absolute;
  left: 20px;
  width: 373px;
}

.iphone .rectangle-2 {
  top: 311px;
  height: 68px;
  background-color: #19bdde;
  border: 1px solid;
  border-color: #000000;
  position: absolute;
  left: 20px;
  width: 373px;
}

.iphone .text-wrapper-2 {
  position: absolute;
  top: 326px;
  left: 102px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #833e3f;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone .rectangle-3 {
  top: 422px;
  height: 54px;
  background-color: #f41515;
  border: 1px solid;
  border-color: #29891a;
  position: absolute;
  left: 20px;
  width: 373px;
}

.iphone .text-wrapper-3 {
  position: absolute;
  top: 504px;
  left: 102px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone .rectangle-4 {
  top: 580px;
  height: 69px;
  background-color: #f51717;
  position: absolute;
  left: 20px;
  width: 373px;
}

.iphone .text-wrapper-4 {
  position: absolute;
  top: 207px;
  left: 124px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone .text-wrapper-5 {
  position: absolute;
  top: 428px;
  left: 95px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone .star-2 {
  position: absolute;
  top: 667px;
  left: 21px;
  width: 55px;
  height: 24px;
}

.iphone .star-3 {
  position: absolute;
  top: 661px;
  left: 349px;
  width: 57px;
  height: 29px;
}

.iphone .text-wrapper-6 {
  position: absolute;
  top: 591px;
  left: 91px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone .text-on-a-path {
  position: absolute;
  top: 572px;
  left: -402px;
  width: 411px;
  height: 78px;
}

box 3

.iphone-plus {
  background-color: #ffffff;
  overflow: hidden;
  width: 100%;
  min-width: 437px;
  min-height: 700px;
  position: relative;
}

.iphone-plus .rectangle {
  position: absolute;
  top: 0;
  left: 0;
  width: 437px;
  height: 63px;
  background-color: #ee3030;
}

.iphone-plus .div {
  position: absolute;
  top: 639px;
  left: 0;
  width: 437px;
  height: 61px;
  background-color: #e22929;
}

.iphone-plus .text-wrapper {
  position: absolute;
  top: 85px;
  left: 9px;
  -webkit-text-stroke: 1px #1c1fdb;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone-plus .line {
  top: 112px;
  left: 156px;
  width: 218px;
  height: 2px;
  position: absolute;
  object-fit: cover;
}

.iphone-plus .text-wrapper-2 {
  position: absolute;
  top: 156px;
  left: 13px;
  -webkit-text-stroke: 1px #e7222c;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone-plus .img {
  top: 193px;
  left: 243px;
  width: 147px;
  height: 2px;
  position: absolute;
  object-fit: cover;
}

.iphone-plus .text-wrapper-3 {
  position: absolute;
  top: 221px;
  left: 13px;
  -webkit-text-stroke: 1px #de1f1f;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #dee81b;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone-plus .line-2 {
  top: 267px;
  left: 272px;
  width: 139px;
  height: 1px;
  position: absolute;
  object-fit: cover;
}

.iphone-plus .text-wrapper-4 {
  position: absolute;
  top: 292px;
  left: -1px;
  -webkit-text-stroke: 1px #ff344c;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #30429a;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone-plus .line-3 {
  top: 340px;
  left: 291px;
  width: 120px;
  height: 1px;
  position: absolute;
  object-fit: cover;
}

.iphone-plus .rectangle-2 {
  position: absolute;
  top: 378px;
  left: 14px;
  width: 409px;
  height: 78px;
  background-color: #f3ff18;
}

.iphone-plus .text-wrapper-5 {
  position: absolute;
  top: 393px;
  left: 123px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #f10e0e;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone-plus .text-wrapper-6 {
  position: absolute;
  top: 507px;
  left: 14px;
  -webkit-text-stroke: 1px #fbe018;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #ee0d0d;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone-plus .text-wrapper-7 {
  position: absolute;
  top: 573px;
  left: 155px;
  -webkit-text-stroke: 1px #24b4e4;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #571ac8;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}



```


## OUTPUT:

![alt text](<Screenshot (59).png>)


## RESULT:
The program to design, develop and deploy a web application for event registration using Figma UI tool is completed successfully.

# Ex08 Event Registration Web Application
## Date:19/12/2025

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
PAGE-1

index.html

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone-pro">
      <div class="rectangle"></div>
      <div class="text-wrapper">EVENT REGISTRATION</div>
      <div class="div"></div>
      <img class="img" src="img/rectangle-4.png" />
      <p class="p">Designed by LOGA SRI M-(25012855)</p>
      <div class="frame"><div class="text-wrapper-2">CULTURAL EVENT</div></div>
      <div class="div-wrapper"><div class="text-wrapper-3">USER NAME</div></div>
      <div class="frame-2"><div class="text-wrapper-4">PASSWORD</div></div>
      <img class="rectangle-2" src="img/rectangle-5.svg" />
      <div class="text-wrapper-5">LOG IN</div>
      <img class="rectangle-3" src="img/rectangle-20.png" />
    </div>
  </body>
</html>


globals.css

@import url("https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css");
* {
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}
html,
body {
  margin: 0px;
  height: 100%;
}
/* a blue color as a generic focus style */
button:focus-visible {
  outline: 2px solid #4a90e2 !important;
  outline: -webkit-focus-ring-color auto 5px !important;
}
a {
  text-decoration: none;
}


style.css

.iphone-pro {
  background-color: #ffffff;
  overflow: hidden;
  width: 100%;
  min-width: 402px;
  min-height: 874px;
  position: relative;
}

.iphone-pro .rectangle {
  position: absolute;
  top: 0;
  left: 0;
  width: 402px;
  height: 52px;
  background-color: #000000;
}

.iphone-pro .text-wrapper {
  position: absolute;
  top: 11px;
  left: calc(50.00% - 133px);
  font-family: "Inter-ExtraBold", Helvetica;
  font-weight: 800;
  color: #ffffff;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro .div {
  position: absolute;
  top: 831px;
  left: 1px;
  width: 402px;
  height: 43px;
  background-color: #b4b4b4;
}

.iphone-pro .img {
  position: absolute;
  top: 151px;
  left: 113px;
  width: 178px;
  height: 168px;
  object-fit: cover;
}

.iphone-pro .p {
  position: absolute;
  top: 843px;
  left: 58px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 16px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone-pro .frame {
  top: 375px;
  left: 43px;
  width: 316px;
  height: 62px;
  background-color: #3e3e3e;
  position: absolute;
  display: flex;
}

.iphone-pro .text-wrapper-2 {
  margin-top: 11px;
  width: 282px;
  height: 39px;
  margin-left: 18px;
  font-family: "Inter-Medium", Helvetica;
  font-weight: 500;
  color: #ffffff;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro .div-wrapper {
  top: 474px;
  left: 46px;
  width: 310px;
  height: 38px;
  background-color: #ac8e8e;
  position: absolute;
  display: flex;
}

.iphone-pro .text-wrapper-3 {
  margin-top: 4px;
  width: 139px;
  height: 29px;
  margin-left: 85px;
  font-family: "Inter-Light", Helvetica;
  font-weight: 300;
  color: #ffffff;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro .frame-2 {
  top: 541px;
  left: 47px;
  width: 310px;
  height: 38px;
  background-color: #ac8e8e;
  position: absolute;
  display: flex;
}

.iphone-pro .text-wrapper-4 {
  margin-top: 4px;
  width: 132px;
  height: 29px;
  margin-left: 89px;
  font-family: "Inter-Light", Helvetica;
  font-weight: 300;
  color: #ffffff;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro .rectangle-2 {
  position: absolute;
  top: 632px;
  left: 144px;
  width: 105px;
  height: 29px;
}

.iphone-pro .text-wrapper-5 {
  position: absolute;
  top: 635px;
  left: 162px;
  font-family: "Inter-Light", Helvetica;
  font-weight: 300;
  color: #ffffff;
  font-size: 20px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone-pro .rectangle-3 {
  position: absolute;
  top: 69px;
  left: 0;
  width: 402px;
  height: 53px;
  object-fit: cover;
}
 
```
```

PAGE-2

index.html

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone-pro">
      <div class="rectangle"></div>
      <div class="text-wrapper">CHOOSE YOUR EVENT</div>
      <div class="div"></div>
      <p class="p">Designed by LOGA SRI M-(25012855)</p>
      <div class="rectangle-2"></div>
      <div class="rectangle-3"></div>
      <div class="rectangle-4"></div>
      <div class="rectangle-5"></div>
      <div class="rectangle-6"></div>
      <div class="rectangle-7"></div>
      <div class="rectangle-8"></div>
      <div class="text-wrapper-2">VOLUNTEER</div>
      <div class="text-wrapper-3">DANCE</div>
      <div class="text-wrapper-4">SINGING</div>
      <div class="text-wrapper-5">INSTRUMENT</div>
      <div class="text-wrapper-6">MIME SHOW</div>
      <div class="text-wrapper-7">RAMP WALK</div>
      <div class="text-wrapper-8">STALL</div>
      <img class="img" src="img/rectangle-21.png" />
    </div>
  </body>
</html>


globals.css

@import url("https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css");
* {
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}
html,
body {
  margin: 0px;
  height: 100%;
}
/* a blue color as a generic focus style */
button:focus-visible {
  outline: 2px solid #4a90e2 !important;
  outline: -webkit-focus-ring-color auto 5px !important;
}
a {
  text-decoration: none;
}

style.css

.iphone-pro {
  background-color: #ffffff;
  width: 100%;
  min-width: 402px;
  min-height: 874px;
  position: relative;
}

.iphone-pro .rectangle {
  position: absolute;
  top: 0;
  left: 0;
  width: 402px;
  height: 52px;
  background-color: #000000;
}

.iphone-pro .text-wrapper {
  position: absolute;
  top: 11px;
  left: 68px;
  font-family: "Inter-ExtraBold", Helvetica;
  font-weight: 800;
  color: #ffffff;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro .div {
  position: absolute;
  top: 831px;
  left: 0;
  width: 402px;
  height: 43px;
  background-color: #b4b4b4;
}

.iphone-pro .p {
  position: absolute;
  top: 843px;
  left: 58px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 16px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone-pro .rectangle-2 {
  position: absolute;
  top: 185px;
  left: 21px;
  width: 360px;
  height: 39px;
  background-color: #ac8e8e;
}

.iphone-pro .rectangle-3 {
  position: absolute;
  top: 563px;
  left: 23px;
  width: 360px;
  height: 39px;
  background-color: #ac8e8e;
}

.iphone-pro .rectangle-4 {
  position: absolute;
  top: 311px;
  left: 21px;
  width: 360px;
  height: 39px;
  background-color: #ac8e8e;
}

.iphone-pro .rectangle-5 {
  position: absolute;
  top: 374px;
  left: 21px;
  width: 360px;
  height: 39px;
  background-color: #ac8e8e;
}

.iphone-pro .rectangle-6 {
  position: absolute;
  top: 437px;
  left: 21px;
  width: 360px;
  height: 39px;
  background-color: #ac8e8e;
}

.iphone-pro .rectangle-7 {
  position: absolute;
  top: 500px;
  left: 21px;
  width: 360px;
  height: 39px;
  background-color: #ac8e8e;
}

.iphone-pro .rectangle-8 {
  position: absolute;
  top: 248px;
  left: 21px;
  width: 360px;
  height: 39px;
  background-color: #ac8e8e;
}

.iphone-pro .text-wrapper-2 {
  position: absolute;
  top: 190px;
  left: 129px;
  font-family: "Inter-Medium", Helvetica;
  font-weight: 500;
  color: #000000;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro .text-wrapper-3 {
  position: absolute;
  top: 253px;
  left: 159px;
  font-family: "Inter-Medium", Helvetica;
  font-weight: 500;
  color: #000000;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro .text-wrapper-4 {
  position: absolute;
  top: 316px;
  left: 147px;
  width: 112px;
  font-family: "Inter-Medium", Helvetica;
  font-weight: 500;
  color: #000000;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro .text-wrapper-5 {
  position: absolute;
  top: 379px;
  left: 123px;
  font-family: "Inter-Medium", Helvetica;
  font-weight: 500;
  color: #000000;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro .text-wrapper-6 {
  position: absolute;
  top: 442px;
  left: 130px;
  font-family: "Inter-Medium", Helvetica;
  font-weight: 500;
  color: #000000;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro .text-wrapper-7 {
  position: absolute;
  top: 505px;
  left: 132px;
  font-family: "Inter-Medium", Helvetica;
  font-weight: 500;
  color: #000000;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro .text-wrapper-8 {
  position: absolute;
  top: 568px;
  left: 164px;
  font-family: "Inter-Medium", Helvetica;
  font-weight: 500;
  color: #000000;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro .img {
  position: absolute;
  top: 632px;
  left: 61px;
  width: 284px;
  height: 163px;
  object-fit: cover;
}

```
```
PAGE-3

index.html

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone-pro">
      <div class="rectangle"></div>
      <div class="div"></div>
      <p class="text-wrapper">Designed by LOGA SRI M-(25012855)</p>
      <div class="text-wrapper-2">REGISTRATION</div>
      <div class="rectangle-2"></div>
      <div class="rectangle-3"></div>
      <div class="text-wrapper-3">EMAIL ID</div>
      <div class="rectangle-4"></div>
      <div class="rectangle-5"></div>
      <div class="rectangle-6"></div>
      <div class="text-wrapper-4">REGISTER NUMBER</div>
      <div class="text-wrapper-5">NAME</div>
      <div class="text-wrapper-6">DEPARTMENT</div>
      <div class="text-wrapper-7">PHONE NUMBER</div>
      <div class="rectangle-7"></div>
      <div class="text-wrapper-8">RESERVE</div>
    </div>
  </body>
</html>

globals.css

@import url("https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css");
* {
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}
html,
body {
  margin: 0px;
  height: 100%;
}
/* a blue color as a generic focus style */
button:focus-visible {
  outline: 2px solid #4a90e2 !important;
  outline: -webkit-focus-ring-color auto 5px !important;
}
a {
  text-decoration: none;
}

style.css

.iphone-pro {
  background-color: #ffffff;
  width: 100%;
  min-width: 402px;
  min-height: 874px;
  position: relative;
}

.iphone-pro .rectangle {
  position: absolute;
  top: 0;
  left: 0;
  width: 402px;
  height: 52px;
  background-color: #000000;
}

.iphone-pro .div {
  position: absolute;
  top: 831px;
  left: 0;
  width: 402px;
  height: 43px;
  background-color: #b4b4b4;
}

.iphone-pro .text-wrapper {
  position: absolute;
  top: 843px;
  left: 58px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 16px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone-pro .text-wrapper-2 {
  position: absolute;
  top: 11px;
  left: 111px;
  font-family: "Inter-ExtraBold", Helvetica;
  font-weight: 800;
  color: #ffffff;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro .rectangle-2 {
  position: absolute;
  top: 130px;
  left: 35px;
  width: 332px;
  height: 56px;
  background-color: #f2e1e1;
  border: 1px solid;
  border-color: #000000;
}

.iphone-pro .rectangle-3 {
  position: absolute;
  top: 454px;
  left: 35px;
  width: 332px;
  height: 56px;
  background-color: #f2e1e1;
  border: 1px solid;
  border-color: #000000;
}

.iphone-pro .text-wrapper-3 {
  position: absolute;
  top: 468px;
  left: 150px;
  font-family: "Inter-Light", Helvetica;
  font-weight: 300;
  color: #000000;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro .rectangle-4 {
  position: absolute;
  top: 373px;
  left: 35px;
  width: 332px;
  height: 56px;
  background-color: #f2e1e1;
  border: 1px solid;
  border-color: #000000;
}

.iphone-pro .rectangle-5 {
  position: absolute;
  top: 292px;
  left: 35px;
  width: 332px;
  height: 56px;
  background-color: #f2e1e1;
  border: 1px solid;
  border-color: #000000;
}

.iphone-pro .rectangle-6 {
  position: absolute;
  top: 211px;
  left: 35px;
  width: 332px;
  height: 56px;
  background-color: #f2e1e1;
  border: 1px solid;
  border-color: #000000;
}

.iphone-pro .text-wrapper-4 {
  position: absolute;
  top: 224px;
  left: 92px;
  font-family: "Inter-Light", Helvetica;
  font-weight: 300;
  color: #000000;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro .text-wrapper-5 {
  position: absolute;
  top: 143px;
  left: 166px;
  font-family: "Inter-Light", Helvetica;
  font-weight: 300;
  color: #000000;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro .text-wrapper-6 {
  position: absolute;
  top: 306px;
  left: 121px;
  font-family: "Inter-Light", Helvetica;
  font-weight: 300;
  color: #000000;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro .text-wrapper-7 {
  position: absolute;
  top: 387px;
  left: 104px;
  font-family: "Inter-Light", Helvetica;
  font-weight: 300;
  color: #000000;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro .rectangle-7 {
  position: absolute;
  top: 605px;
  left: 84px;
  width: 234px;
  height: 38px;
  background-color: #4e4a4a;
}

.iphone-pro .text-wrapper-8 {
  position: absolute;
  top: 609px;
  left: 149px;
  font-family: "Inter-ExtraBold", Helvetica;
  font-weight: 800;
  color: #ffffff;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

```

## OUTPUT:

![alt text](<Screenshot (58).png>)

## RESULT:
The program to design, develop and deploy a web application for event registration using Figma UI tool is completed successfully.

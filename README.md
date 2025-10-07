# Ex09 Event Registration Web Application
# Date:07.10.2025
# AIM:
To design, develop and deploy a web application for event registration.

# DESIGN STEPS:
## Step 1:
Create a new frame.

## Step 2:
Select any one preset size of your choice.

## Step 3:
Select the shapes you need.

## Step 4:
Import images as needed.

## Step 5:
Create pages based on your need and link them.

## Step 6:
Validate the HTML and CSS code.

## Step 6:
Publish the website in the given URL.

# DESIGN TOOL:
Figma

# CODE:
~~~
page 1:

<div style="width: 412px; height: 917px; position: relative; background: white; overflow: hidden">
  <img style="width: 629px; height: 944px; left: -109px; top: -27px; position: absolute" src="https://placehold.co/629x944" />
  <div style="width: 132px; height: 34px; left: 140px; top: 594px; position: absolute; background: #FCE2CA; border-radius: 8px"></div>
  <div style="width: 74px; left: 169px; top: 594px; position: absolute; justify-content: center; display: flex; flex-direction: column; color: #5960E0; font-size: 24px; font-family: Inter; font-weight: 600; line-height: 33.60px; word-wrap: break-word">Login</div>
  <div style="width: 132px; height: 34px; left: 140px; top: 645px; position: absolute; background: #F9DDB5; border-radius: 8px"></div>
  <div style="left: 159px; top: 645px; position: absolute; justify-content: center; display: flex; flex-direction: column; color: #675FF5; font-size: 24px; font-family: Inter; font-weight: 600; line-height: 33.60px; word-wrap: break-word">Register</div>
</div>

page 2:

<div style="width: 412px; height: 917px; position: relative; transform: rotate(180deg); transform-origin: top left; background: white; overflow: hidden">
  <img style="width: 1918px; height: 959px; left: -733px; top: -21px; position: absolute" src="https://placehold.co/1918x959" />
  <div style="width: 349px; height: 107px; left: 401px; top: 228px; position: absolute; transform: rotate(180deg); transform-origin: top left; justify-content: center; display: flex; flex-direction: column; color: black; font-size: 32px; font-family: Inter; font-weight: 600; line-height: 44.80px; word-wrap: break-word">Sports Day Events</div>
  <div style="width: 256px; height: 389px; left: 350px; top: 549px; position: absolute; transform: rotate(180deg); transform-origin: top left; justify-content: center; display: flex; flex-direction: column; color: #1A7EFF; font-size: 20px; font-family: Inter; font-weight: 600; line-height: 32px; letter-spacing: 0.40px; word-wrap: break-word">Cricket<br/>Badminton<br/>Basketball<br/>Volley ball<br/>100 MTS<br/>400 MTS<br/>4*100 Relay</div>
</div>


page 3:

<div style="width: 412px; height: 917px; position: relative; background: white; overflow: hidden">
  <img style="width: 1982px; height: 991px; left: -1482px; top: 0px; position: absolute" src="https://placehold.co/1982x991" />
  <div style="width: 302px; height: 35px; left: 56px; top: 65px; position: absolute; justify-content: center; display: flex; flex-direction: column; color: #4B1A76; font-size: 20px; font-family: Lilita One; font-weight: 400; line-height: 32px; letter-spacing: 0.40px; word-wrap: break-word; text-shadow: 0px 4px 4px rgba(18, 8, 8, 0.25)">EVENT REGISTRATION FORM</div>
  <div style="width: 127px; height: 23px; left: 56px; top: 100px; position: absolute; justify-content: center; display: flex; flex-direction: column; color: black; font-size: 20px; font-family: Life Savers; font-weight: 400; line-height: 32px; letter-spacing: 0.40px; word-wrap: break-word">Fill the  details</div>
  <div style="width: 244px; height: 30px; left: 44px; top: 184px; position: absolute; background: #AB59F3"></div>
  <div style="width: 244px; height: 30px; left: 44px; top: 517px; position: absolute; background: #AB59F3"></div>
  <div style="width: 170px; height: 30px; left: 165px; top: 583px; position: absolute; background: #372248; border-radius: 8px"></div>
  <div style="width: 244px; height: 30px; left: 44px; top: 467px; position: absolute; background: #AB59F3"></div>
  <div style="width: 244px; height: 27px; left: 44px; top: 420px; position: absolute; background: #AB59F3"></div>
  <div style="width: 217px; height: 30px; left: 44px; top: 360px; position: absolute; background: #AB59F3"></div>
  <div style="width: 232px; height: 30px; left: 44px; top: 315px; position: absolute; background: #AB59F3"></div>
  <div style="width: 232px; height: 30px; left: 44px; top: 271px; position: absolute; background: #AB59F3"></div>
  <div style="width: 194px; height: 28px; left: 44px; top: 226px; position: absolute; background: #AB59F3"></div>
  <div style="left: 84px; top: 182px; position: absolute; justify-content: center; display: flex; flex-direction: column; color: white; font-size: 20px; font-family: Linden Hill; font-weight: 400; line-height: 32px; letter-spacing: 0.40px; word-wrap: break-word">Full Name</div>
  <div style="left: 83px; top: 271px; position: absolute; justify-content: center; display: flex; flex-direction: column; color: white; font-size: 20px; font-family: Linden Hill; font-weight: 400; line-height: 32px; letter-spacing: 0.40px; word-wrap: break-word">Age</div>
  <div style="left: 84px; top: 314px; position: absolute; justify-content: center; display: flex; flex-direction: column; color: white; font-size: 20px; font-family: Linden Hill; font-weight: 400; line-height: 32px; letter-spacing: 0.40px; word-wrap: break-word">Register Number</div>
  <div style="left: 84px; top: 226px; position: absolute; justify-content: center; display: flex; flex-direction: column; color: white; font-size: 20px; font-family: Linden Hill; font-weight: 400; line-height: 32px; letter-spacing: 0.40px; word-wrap: break-word">Gender</div>
  <div style="left: 84px; top: 359px; position: absolute; justify-content: center; display: flex; flex-direction: column; color: white; font-size: 20px; font-family: Linden Hill; font-weight: 400; line-height: 32px; letter-spacing: 0.40px; word-wrap: break-word">Department</div>
  <div style="left: 83px; top: 469px; position: absolute; justify-content: center; display: flex; flex-direction: column; color: white; font-size: 20px; font-family: Linden Hill; font-weight: 400; line-height: 32px; letter-spacing: 0.40px; word-wrap: break-word">Email ID</div>
  <div style="left: 80px; top: 420px; position: absolute; justify-content: center; display: flex; flex-direction: column; color: white; font-size: 20px; font-family: Linden Hill; font-weight: 400; line-height: 32px; letter-spacing: 0.40px; word-wrap: break-word">Mobile Number</div>
  <div style="left: 80px; top: 517px; position: absolute; justify-content: center; display: flex; flex-direction: column; color: white; font-size: 20px; font-family: Linden Hill; font-weight: 400; line-height: 32px; letter-spacing: 0.40px; word-wrap: break-word">Events to Register</div>
  <div style="left: 209px; top: 581px; position: absolute; justify-content: center; display: flex; flex-direction: column; color: white; font-size: 20px; font-family: Lilita One; font-weight: 400; line-height: 32px; letter-spacing: 0.40px; word-wrap: break-word">REGISTER</div>
</div>


page 4:

<div style="width: 412px; height: 917px; position: relative; background: white; overflow: hidden">
  <img style="width: 1954px; height: 977px; left: -85px; top: -30px; position: absolute" src="https://placehold.co/1954x977" />
  <div style="width: 280px; height: 65px; left: 98px; top: 230px; position: absolute; justify-content: center; display: flex; flex-direction: column; color: black; font-size: 40px; font-family: Lilita One; font-weight: 400; line-height: 56px; word-wrap: break-word">THANK YOU</div>
  <div style="width: 255px; height: 114px; left: 98px; top: 277px; position: absolute; justify-content: center; display: flex; flex-direction: column; color: black; font-size: 16px; font-family: Libre Franklin; font-weight: 400; line-height: 22.40px; word-wrap: break-word">We are all eagerly waiting for your participation in the sports Events</div>
  <div style="width: 327px; height: 134px; left: 51px; top: 772px; position: absolute; justify-content: center; display: flex; flex-direction: column"><span style="color: black; font-size: 24px; font-family: Libre Franklin; font-weight: 700; line-height: 33.60px; word-wrap: break-word">Contact us:<br/></span><span style="color: black; font-size: 16px; font-family: Libre Franklin; font-weight: 500; line-height: 22.40px; word-wrap: break-word">Email:</span><span style="color: black; font-size: 16px; font-family: Libre Franklin; font-weight: 400; line-height: 22.40px; word-wrap: break-word">                                                                                     </span><span style="color: black; font-size: 16px; font-family: Libre Franklin; font-weight: 500; line-height: 22.40px; word-wrap: break-word">saveethaengineeringcollege@gmail.com<br/></span><span style="color: black; font-size: 16px; font-family: Libre Franklin; font-weight: 400; line-height: 22.40px; word-wrap: break-word">Phone:<br/>         </span><span style="color: black; font-size: 16px; font-family: Libre Franklin; font-weight: 500; line-height: 22.40px; word-wrap: break-word">    9281982778<br/>             3082983874</span></div>
</div>

~~~
# OUTPUT:
![alt text](image1.png)
![alt text](image2.png)
![alt text](image3.png)
![alt text](image4.png)
# RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.

# iOS 6 components for CSS 
Reimplementation of the skeuomorphic design language pioneered by Apple &amp; Scott  

Components:  
- Analog Dial (Clock)  
- Analog Counter (Clock)  
- Delete Prompt (Shredder)  
- Heading (Metalic Reflective)  
- Subheading (Glossy Reflective)  
- Settings List  
- Background Gradients (Settings Wallpaper)  
- Popup Options (Schedule, Siri Prompt)  
  
<div>
    <div style="
    border-radius: 12px;
    /* max-width: 250px; */
    max-width: 13.8em;
    padding: 1rem;
    position: relative;
    background: linear-gradient(45deg, rgb(149,149,149) 45%, rgb(246,246,246) 65%, rgb(149,149,149), rgb(246,246,246));
    padding: 3px;
    ">
    <div style="
        background-image: linear-gradient(45deg, #000 45%, rgb(38,38,38) 65%);
        border-radius: 10px;
        color: white;
        padding: .75rem 1.25rem;
        font-family: sans-serif;
        font-size: 2em;
    ">
        <figcaption style="
        background: linear-gradient(45deg, rgb(149,149,149) 45%, rgb(246,246,246) 65%, rgb(149,149,149), rgb(246,246,246));
        background-clip: text;
        -webkit-background-clip: text;
        color: transparent;
        text-align: center;
        ">
        iOS 6 CSS
        </figcaption>
    </div>
</div>

<br>

<div style="
    width: 150px;
    height: 150px;
    border: 1px solid #f2f2f2;
    background-color: #1d1d1d;
    background-image: 
      radial-gradient(circle at top, #66666666, #49494966 45%, transparent 45%),
      radial-gradient(circle, #262626, #060606);
    border-radius: 50%;
    position: relative;
  ">
    <div style="
    top: 0; left: 0; right: 0; bottom: 0;
    margin: auto;
    width: 8px;
    height: 8px;
    transform: rotateZ(103deg);
    position: absolute;
    ">
      <div style="
        width: 2px;
        height: 45px;
        /* border-left: 1px solid white; */
        background: white;
        margin: auto;
      ">
      </div>
    </div>
    <div style="
    top: 0; left: 0; right: 0; bottom: 0;
    margin: auto;
    width: 8px;
    height: 8px;
    transform: rotateZ(233deg);
    position: absolute;
    ">
      <div style="
        width: 2px;
        height: 35px;
        /* border-left: 1px solid white; */
        background: white;
        margin: auto;
      ">
      </div>
    </div>
    <div style="
      top: 0; left: 0; right: 0; bottom: 0;
      margin: auto;
      width: 8px;
      height: 8px;
      border-radius: 10px;
      background: red;
      transform: rotateZ(33deg);
      position: absolute;
    ">
      <div style="
        width: 1px;
        height: 55px;
        border-left: 1px solid red;
        margin: auto;
      ">
      </div>
    </div>
  </div>

<br>

<div style="max-width: 400px;">
    <div style="
        font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
        max-width: 400px;
        padding: 1rem 0;
        border-radius: 10px;
        text-align: center;
        background: linear-gradient(to right, rgb(111,111,111), rgb(92,92,92) 4px, rgb(198,198,198) 1.5em, rgb(143,143,143) calc(100% - 30%), rgb(193,193,193) calc(100% - 1.5em), rgb(92,92,92) calc(100% - 4px), rgb(111,111,111));
        border: 1px solid #444;
        color: #444;
    ">
        <br>
        <br>
        <br>
        <p style="
        /* background: radial-gradient(circle at center, darkred, red, #222, #222); */
        background: darkred;
        padding: .25em;
        color: transparent;
        text-shadow: 0px 2px 3px rgba(180,180,180,0.5);
        -webkit-background-clip: text;
        -moz-background-clip: text;
        background-clip: text;
        ">
        Warning
        </p>
        <p style="padding: 0 2em; font-weight: normal; font-size: .8em;">
        Removing this calendar event will remove all repititions of this event.
        </p>
        <br>
        <br>
        <br>
    </div> 
    <div style="
        background: white;
        color: #262626;
        margin: 0 2em;
        box-shadow: 0 6px 10px -6px #000 inset;
        border-bottom-right-radius: 2px;
        border-bottom-left-radius: 2px;
        padding: 1em;
        border: 1px solid;
        border-top: none;
        /* background-size: 19px 19px; */
        background-image: url(/images/paper2.jpg);
    ">
        <br>
        <h3>
        9 O' Clock Standup
        </h3>
        <p style="color: #1d1d1d;">
        Days: T
        <br>
        Time: 9:00 AM
        <br>
        @ 6 Suite Complex
        </p>
        <br>
    </div> 
</div>

<br>

<div style="
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
    padding: 1rem 0;
    border-radius: 10px;
    max-width: 400px;
    background: 
      linear-gradient(
        rgb(149, 157, 169), rgb(67,70,84) 50%, 
        rgb(31,34,46) calc(50% + 2px), rgb(40,42,45));
    border: 1px solid #666;
    padding: .5em;
  ">
    <div style="
      border-radius: 10px;
      background: white;
      box-shadow: 0 3rem 4.5rem -2rem #000 inset, 0 -3rem 4.5rem -2rem #000 inset;
      display: grid;
      grid-template-columns: 4px auto 4px 4px 4px auto 4px 4px 4px auto 4px;
      font-size: 3em;
      font-weight: 500;
      position: relative;
      padding: 0;
      overflow: hidden;
    ">
      <div style="background: linear-gradient(rgb(52,52,63), rgb(198, 198, 215), rgb(52,52,63));"> </div>
      <div style="text-align: right; padding: 0 .25em;">
        3 <br> 4 <br> 5 <br> 6 <br> 7
      </div>
      <div style="background: linear-gradient(rgb(52,52,63), rgb(198, 198, 215), rgb(52,52,63));"> </div>
      <div style="background: black;"> </div>
      <div style="background: linear-gradient(rgb(52,52,63), rgb(198, 198, 215), rgb(52,52,63));"> </div>
      <div style="padding: 0 .25em;">
        58 <br> 59 <br> 00 <br> 01 <br> 02
      </div>
      <div style="background: linear-gradient(rgb(52,52,63), rgb(198, 198, 215), rgb(52,52,63));"> </div>
      <div style="background: black;"> </div>
      <div style="background: linear-gradient(rgb(52,52,63), rgb(198, 198, 215), rgb(52,52,63));"> </div>
      <div style="padding: 0 .25em;">
         <br>  <br> AM <br> PM <br> 
      </div>
      <div style="background: linear-gradient(rgb(52,52,63), rgb(198, 198, 215), rgb(52,52,63));"> </div>
    </div>
  </div> 

<br>
## How to:  
These are written with vanilla css and html in mind. Copy and paste / drop-in usability. Each file holds in itself all the text required to recreate them. A component would have the content in `<html><body> <!-- Component HTML --> </body></html>`. The CSS styling for the component may be partly inline and partly in `<style>` tags: `<html><head><style> /* Component CSS */ </style></head></body>`.  
  
## Examples:  
You can find the collection hosted at [a website I have push access to PrettySights](https://prettysights.com/vsads/css-lounge/)
  
## Usage:  
I made these bc I love iOS 6 v v much. I have an iPod 4 y it makes me smile to see all the parallels to real-world design. These components can be modified and used in any way.  
  
## Plans:  
- Review the work of Alejandro Burón, Eli Schiff, Cole Rise, and Scott Forstall  
- Add documentation  
- Build our components in Vue & React  
- Simplify CSS  

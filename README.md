
<div align="center">

<a href="https://www.facebook.com/profile.php?id=100079286477497locale=ar_AR">
<img src="https://github.com/Yosef-Eid/Yosef-Eid/assets/117477110/d0ec59c4-60db-4b45-a632-7c9053bdb15d">
</a>
 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<a href="https://www.linkedin.com/in/yousef-eid-080b75290/">
<img src="https://github.com/Yosef-Eid/Yosef-Eid/assets/117477110/e1136458-0bfa-4c9d-895f-cffd6b6fe16b">
</a>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<a href="https://www.twitter.com/rzashakeri/">
<img src="https://github.com/Yosef-Eid/Yosef-Eid/assets/117477110/4a2b9734-89ad-4b3d-adf6-e445ae5bdf2a">
</a>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<a href="https://www.linkedin.com/in/rezshakeri/">
<img src="https://github.com/Yosef-Eid/Yosef-Eid/assets/117477110/77a117ba-f200-4d05-83d5-10b03bbbe8f4">
</a>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<a href="https://t.me/Yousef_Eid2">
<img src="https://github.com/Yosef-Eid/Yosef-Eid/assets/117477110/5fec61ae-4280-4c0d-931c-4eb8f6121ee0">
</a>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<a href="https://mail.google.com/mail/u/0/?tab=rm&ogbl#inbox">
<img src="https://github.com/Yosef-Eid/Yosef-Eid/assets/117477110/5eeb8566-0239-46c6-baf0-f1ddfd6273dc">
</a>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<a href="https://app.slack.com/client/T04TKKU2LBW/D04TH68S84A">
<img src="https://github.com/Yosef-Eid/Yosef-Eid/assets/117477110/bfeeff6c-6547-4143-99cd-bb6082f8f9f4">
</a>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<a href="https://discordapp.com/users/1142169445754748948">
<img src="https://github.com/Yosef-Eid/Yosef-Eid/assets/117477110/c91ee0f0-5949-4fa4-b8d3-9d6a6bb7ad53">
</a>
</div>

<br>

<div align='center'>
  <img  src='https://github.com/Yosef-Eid/joscript/assets/117477110/2abd752c-6128-4b26-9e41-dc11ef3acadc'/>  
</div>

<h1>What is Joscript</h1>

<ul>
<li>
 Joscript is an open source Javascript library that simplifies JavaScript code. It is dedicated to building and developing user interfaces on websites. The advantage of Joscript is that it does not impose a   
    specific style on the user; It works the way the user wants
</li>
<li>Jocript is easy to use even for beginners. It provides a set of tools and components that can be used to shorten javasceipt code to create attractive and interactive user interfaces.</li>
 </ul>

 <h1>Example</h1>
 <p>Accordingly, Welcome to joscript will be displayed in your browser</p>
 
 ```jsx
import { jo } from "../../joscript/joScript.js";


function App() {let load = window.onload = () => {

    return(
        jo('div', {class:'app ', id:'app' ,children:[

            jo('h1', {text:'Welcome to joscript'}),
           
        ]})
    )

};return load()}
export default App;
 ```

 <h1>JoScript features</h1>
 <div>
  1 - Makes it easier to write HTML code inside Javascript
  
  ```jsx
  jo('h1', {id:'h1', class:'h1', text:'welcome to joscript'})
  ```
 </div>

  <div>
  2 - Make it easier to call elements within Javascript
  
  ```jsx
  getId('h1'),
  getClass('h1'),
  getName('h1'),

  querySelector('.h1'), // Here you can call elements like CSS
  querySelectorAll('.h1'), // Here you can call elements like CSS


  ```
 </div>
<!---
jo-script/jo-script is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

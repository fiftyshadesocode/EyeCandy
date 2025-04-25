![Eyecandy Theme](https://github.com/user-attachments/assets/dd58889d-03ce-4dad-a04b-98269f1c4611)

<em>Eyecandy transforms your browsing experience with stunning visuals and transparency, creating a modern, elegant look that enhances your interaction with the web while maintaining readability and practicality.</em>
See it to believe it!!

<details>
  <summary>New Tab Page</summary>
  <img width="960" alt="2025-04-25" src="https://github.com/user-attachments/assets/3e1cfd4e-5caf-442e-8a68-721136c477fa" />
<img width="960" alt="2025-04-25 (1)" src="https://github.com/user-attachments/assets/a6046824-6514-4a14-a3c0-6f1fab2bebbd" />
</details>

<details><summary>Youtube Music</summary>
<img width="960" alt="2025-04-25 (8)" src="https://github.com/user-attachments/assets/2c05d773-e8c2-43f4-ac2d-a48f31d9ed74" />
<img width="960" alt="2025-04-25 (5)" src="https://github.com/user-attachments/assets/e522ace2-bcb4-4010-9823-6ede137bb288" />
</details>

<details><summary>Youtube</summary>
<img width="960" alt="2025-04-25 (9)" src="https://github.com/user-attachments/assets/d4665614-450a-47e9-9bf5-8a8ed648df6e" />

</details>

<details><summary>Reddit</summary>
<img width="960" alt="2025-04-25 (11)" src="https://github.com/user-attachments/assets/4381826f-935b-4558-b9bb-0bbedf90a7d1" />
<img width="960" alt="2025-04-25 (12)" src="https://github.com/user-attachments/assets/fc9ec1fb-d3fb-41bd-8f80-a8461869357c" />

</details>

<details><summary>Github</summary>
<img width="960" alt="2025-04-25 (13)" src="https://github.com/user-attachments/assets/0e81e0f1-c87d-42bb-aa69-6872b215d50a" />
<img width="960" alt="2025-04-25 (14)" src="https://github.com/user-attachments/assets/49b3cc7f-c196-409d-98c5-a78378bb9002" />

</details>


(will upload video later)

Like the theme? 
Follow the steps below to acheive it!!

**Step 1: Ready Zen:**<br>
[1.1] About Config changes<br>
-->Go to about:config and set following toggles to true<br>
<code>browser.tabs.allow_transparent_browser</code><br>
<code>devtools.debugger.remote-enabled</code><br>

[1.2] Creating chrome folder<br>
-->Type about:support in the address bar and press Enter<br>
  Look for the Application Basics section<br>
  Click on Open Profile Folder. This will open the folder where Zen Browser stores your user data<br>

-->In the Profile Folder, create a new folder and name it chrome<br>
   Inside the chrome folder, create a new blank file named userChrome.css<br>
   Restart Zen Browser to apply the changes<br>


**Step 2: Adding the backdrop:**<br>
[2.1] Opening devtools
-->Press the key combination of ctrl+shift+alt+I<br>
   two dialog boxes will appear press ok in the one asking for permission<br>
   Go to the style editor tab and search for userChrome.css<br>
   
[2.2] Adding the code
--> Paste the following css
  
    #main-window{
    background:  url(link_to_image) !important;
    display: block !important;
    width:100vw;
    height:auto;
    background-repeat:no-repeat; }
    #browser {
    background: rgba(0, 0, 0, 0) !important;
    backdrop-filter: blur(10px);  }


--> replace the text 'link_to_image' by either the link to the image or the path to the image<br>
/NOTE: Local images will require a restart of the browser/


**Step 3: Making the websites transparent:**<br>
[3.1] Installing the injector<br>
--> Install the stylus extention from the following link https://addons.mozilla.org/en-US/firefox/addon/styl-us/<br>

[3.2] Adding the styles<br>
--> Click on the extention menu button and then click on stylus <br>

/NOTE: open a website like google when you do this, as there are some sites which the browser restricts access to and you will not see the manage button on those/<br>

Click on manage button<br>
Click on Write new style<br>
Paste the css for any one website from this repo<br>
Click on owerwrite style<br>
In the top left add a name and Click on Save<br>

**Repeat for each website**
    

   

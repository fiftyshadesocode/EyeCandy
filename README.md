![Eyecandy Theme](https://github.com/user-attachments/assets/dd58889d-03ce-4dad-a04b-98269f1c4611)

<em>Eyecandy transforms your browsing experience with stunning visuals and transparency, creating a modern, elegant look that enhances your interaction with the web while maintaining readability and practicality.</em><br>
See it to believe it!!

<details>
  <summary>New Tab Page</summary>
  <img width="480" alt="2025-04-25" src="https://github.com/user-attachments/assets/3e1cfd4e-5caf-442e-8a68-721136c477fa" />
<img width="480" alt="2025-04-25 (1)" src="https://github.com/user-attachments/assets/a6046824-6514-4a14-a3c0-6f1fab2bebbd" />
</details>

<details><summary>Youtube Music</summary>
<img width="480" alt="2025-04-25 (8)" src="https://github.com/user-attachments/assets/2c05d773-e8c2-43f4-ac2d-a48f31d9ed74" />
<img width="480" alt="2025-04-25 (16)" src="https://github.com/user-attachments/assets/20185dcd-94b4-4867-8f2a-f54b8ece2079" />

</details>

<details><summary>Youtube</summary>
<img width="480" alt="2025-04-25 (9)" src="https://github.com/user-attachments/assets/d4665614-450a-47e9-9bf5-8a8ed648df6e" />

</details>

<details><summary>Reddit</summary>
<img width="480" alt="2025-04-25 (11)" src="https://github.com/user-attachments/assets/4381826f-935b-4558-b9bb-0bbedf90a7d1" />
<img width="480" alt="2025-04-25 (12)" src="https://github.com/user-attachments/assets/fc9ec1fb-d3fb-41bd-8f80-a8461869357c" />

</details>

<details><summary>Github</summary>
<img width="480" alt="2025-04-25 (13)" src="https://github.com/user-attachments/assets/0e81e0f1-c87d-42bb-aa69-6872b215d50a" />
<img width="480" alt="2025-04-25 (14)" src="https://github.com/user-attachments/assets/49b3cc7f-c196-409d-98c5-a78378bb9002" />

</details>


(will upload video later)

Like the theme? <br>
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
[2.1] Opening devtools<br>
-->Press the key combination of ctrl+shift+alt+I<br>
   two dialog boxes will appear press ok in the one asking for permission<br>
   Go to the style editor tab and search for userChrome.css
   
[2.2] Adding the code<br>
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
    
<details><summary>!! Bonus: You can set a keybind to toggle transparency by following the steps below !!</summary>
Open settings go to extentions<br>
Click on the three dots next to stylus<br>
Click manage <br>
Now click on the gear icon in the top right<br>
Click on Manage Extension Shortcuts<br>
Now scroll and find the turn all styles off shortcut and set it to whatever you like!
</details>

Doing this much will acheive transparency however if you want the full eyecandy experience follow the steps below as well

**Optional Step 1: Enabling and configuring the new tab page**<br>
[O_1.1] Enable new tab page<br>
--> Go to about config and set zen.urlbar.replace-newtab to false

[O_1.2] Configuring the page <br>
--> Dowload the bonjurr extentions from the link https://addons.mozilla.org/en-US/firefox/addon/bonjourr-startpage/ <br>
    Click on the settings icon scroll down to the custom css section and add the following css

    body{background:#fff0}
    #background_overlay{background:#fff0}
    #background{background:#fff0 !important}
    #credit{display:none}

**Optional Step 2: Adding my tweaks to the UI**<br>
--> Copy the css from the userChrome.css file in this repo and add to the browser by following the procedure given in Step2<br>
    Read through the comments the black colored text enclosed as such /* */ <br>
    And anything you want to disable just select it and press ctrl+/ to exclude it<br>

/Note: if you decide to keep the icon changes you will have to download the icons from the icons folder in this repo and paste it in the chrome folder/<br>
/Also true if you do decide to keep the updated media player animation/

**I also recommend installing the following mods and extentions**<br>
- Playback Speed: This extension allows you to control the speed of video playback on various websites, making it easier to watch videos at your preferred pace.<br>
https://addons.mozilla.org/en-US/firefox/addon/playback-speed/<br>
- Return YouTube Dislikes: It restores the ability to view dislike statistics on YouTube videos, giving you a better sense of community feedback.<br>
https://addons.mozilla.org/en-US/firefox/addon/return-youtube-dislikes/<br>
- Better Lyrics: Enhance your YouTube Music experience with time-synced lyrics, multilingual support, and real-time translations. It even lets you seek specific parts of a song by clicking on the lyrics.<br>
https://addons.mozilla.org/en-US/firefox/addon/better-lyrics/<br>

Feel free to let me know if there are any issue as this is very much in active development

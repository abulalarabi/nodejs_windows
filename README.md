# nodejs and npm installation on Windows
Follow the steps carefully. This tutorial is especially created for Human-Computer Interaction CSCE436 Tamu, Spring 23 course. Yet, it will apply to anyone who wants to install nodejs and npm on windows machine, run a local server, and play around with p5.js.

## Pre-requisite 
Remove any prior installation of node or npm on your computer, including any WSL (ubuntu or other) terminal installation. To unistall node from terminal you can run `sudo apt remove nodejs`.

## Download Nodejs
Go to [Nodejs official site](https://nodejs.org/en/download/) and download the latest version.

![](https://github.com/abulalarabi/nodejs_windows/raw/main/figures/nodejs_windows/Slide1.PNG)

## Run the installer
  * Step 1: Press next and accept license agreement.
   
  ![](https://github.com/abulalarabi/nodejs_windows/raw/main/figures/nodejs_windows/Slide2.PNG)

  * Step 2 !!!IMPORTANT!!!: Click on the drive icon beside _npm package manager_ and select _Entire feature will be installed on local hard drive_.
 
 ![](https://github.com/abulalarabi/nodejs_windows/raw/main/figures/nodejs_windows/Slide3.PNG)

  * Step 3 !!!IMPORTANT!!!: Do the same for _Add to PATH_.
  
  ![](https://github.com/abulalarabi/nodejs_windows/raw/main/figures/nodejs_windows/Slide4.PNG)
  
  * Step 4 !!!IMPORTANT!!!: Select the _Automatically install ..._ option and click _Next_.

   ![](https://github.com/abulalarabi/nodejs_windows/raw/main/figures/nodejs_windows/Slide5.PNG)

  * Step 5: You will prompted with _Press any key to continue_, press any button on your keyboard.

  ![](https://github.com/abulalarabi/nodejs_windows/raw/main/figures/nodejs_windows/Slide6.PNG)
  
  * Step 6: Once done, you have type _ENTER_ on the terminal and then press the ENTER button on your keyboard.
  
  ![](https://github.com/abulalarabi/nodejs_windows/raw/main/figures/nodejs_windows/Slide7.PNG)
  
## Testing Installation
  * Step 1: Search for _Terminal_ or _Power Shell_ and open it.

  ![](https://github.com/abulalarabi/nodejs_windows/raw/main/figures/nodejs_windows/Slide8.PNG)
  
  * Step 2: Type the following commands one by one:
  ```
  npm -v
  ```
  ```
  node -v
  ```
  
  They should produce output something like this:
  
  ![](https://github.com/abulalarabi/nodejs_windows/raw/main/figures/nodejs_windows/Slide9.PNG)
  
  If there is any error go back to the beginning of the tutorial and follow the instructions again. 

## Running local server for p5js:
  * Step 1: Download the pre-configured p5js zip from [HERE](https://github.com/abulalarabi/nodejs_windows/raw/main/p5js_windows.zip) and extract the zip. DO NOT change the folder structure for now, it is already pre-structured.
  * Step 2: Inside the extracted folder press _Shift Key_ and _Right Click_ to open the dialog box and select _Open PoerShell window here_. Alternately, you can run powershell from the start menu and navigate to the directory of the extracted folder.

  ![](https://github.com/abulalarabi/nodejs_windows/raw/main/figures/nodejs_windows/Slide10.PNG)
  
  * Step 3: Run the following commands one by one:
  ```
  npm install npm@latest -g
  ```
  ```
  npm install express --save
  ```
  
  * Step 4: Now run the local server by typing the following command (you do not need to change or create app.js, it is already pre-configured):
  ```
  node app.js
  ```
  
   !!! if you are asked to allow firewall, select both the checkbox and click _Allow access_. !!!
  
  ![](https://github.com/abulalarabi/nodejs_windows/raw/main/figures/nodejs_windows/Slide14.PNG)
  
  * Step 5: Open a browser (Chrome Preferred) and enter the url [127.0.0.1:3000](127.0.0.1:3000) and click on _click me_. It should bring a logo similar to the following figure:
  
  ![](https://github.com/abulalarabi/nodejs_windows/raw/main/figures/nodejs_windows/Slide15.PNG)

## Editing p5js:
Similar to the tutorial shown in the class, you can edit the _sketch.js_ file and refresh the browser to reflect the changes.

## Additional Troubleshooting:
Turning off and on your computer (restart) is always an option :wink:.



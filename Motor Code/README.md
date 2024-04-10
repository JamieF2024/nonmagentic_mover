<h1>Motor Code Overview</h1>
The motor assembly utilizes a WLG-75-R piezoelectric motor to generate rotational motion. This motor is controlled by a WLG-75-R-AMAG and Nucleo Board F446RE. The motor code is written in C++. It can be edited, uploaded, and run through <a href="https://studio.keil.arm.com/">Keil Studio Cloud - Arm</a>. Below are instructions for how to set up and run the main.cpp files in this folder.
<h2>Setup</h2>
<ol>
  <li>Login or Create an Account with Keil Studio Cloud.</li>
  <li>In the top right, go to File -> New -> Mbed Project.</li>
  <li>For the "Example project" field, select "empty Mbed OS project". Edit the project name to something memorable. The project should now appear as <b>active</b> in the left panel.</li>
  <li>Right click on the project name in the left panel and select Add Mbed Library.</li>
  <li> For the "URL" field, use <a href=http://os.mbed.com/users/aberk/code/QEI/>http://os.mbed.com/users/aberk/code/QEI/</a>. The Library Name field should auto-populate as "QEI". </li>
  <li>Click Next. For the "Release, Branch, or Tag" field, select "default". Click Finish. There should now be a subfolder labeled QEI. This folder contains 2 files: QEI.cpp & QEI.h.</li>
  <li>Replace the current QEI.cpp and QEI.h files in Keil Studio Cloud with the files in the GitHub Motor Code folder. You can do this by either downloading then uloading the files, or by copying and pasting their contents.</li>
  <li>Do the same for the main.cpp file found in Keil Studio Cloud and this GitHub folder.</li>
<i>Note: the main.cpp file is currently not uploaded in GitHub. Please use the Google Drive.</i>
</ol>
<b>You have now successfully finished the setup!</b>
<h2>Building & Running a Program</h2>
<i>When working in Keil Studio Cloud, make sure that the project you are working on is <b>active</b>.</i>
<ol>
  <li> Plug the Nucleo Board into the computer you are using with Keil Studio Cloud.</li>
  <li>Ensure your current project is <b>active</b>. Set the "Build target" in the left pane as "NUCLEO-F446RE".</li>
  <li>Build the project using the blue hammer button in the left pane. This will take around a minute the first time you build, but in future builds it will be quicker. Upon completion, a download should be completed as a ".bin" file.</li>
  <li> Open file explorer. Find the Nucleo Board connection under "This PC". Drag and drop the ".bin" file into the Nucleo drive.</li>
</ol>
<b>Your code is now successfully uploaded and running!</b>

.. raw:: html

   <h1 align="center">

.. image:: ./pictures/scrk.png
 	:width: 700px
 	:alt: Project

.. raw:: html

   <br class="title">
   KILLER PROJECT
   <br>
  </h1>

.. contents:: 
    :local:
    :depth: 1

=============
INTRO
=============

#screenshot #pentest #OSCP 

This script was to developed to capture screenshot during pentest engagment and OSCP.

IMPORTANT: The screenshot feature is no longer allowed for exam but the terminal logging is allowed for exam.

If you like the tool and for my personal motivation so as to develop other tools please a +1 star * 

The tool can be used by pentesters, CTF players, students and trolls :).

**WARNING: SCREEN_KILLER is part of the KILLER project. SCREEN_KILLER is still under development 
and there might be some issues, please create an issue if you found any. **

**Other tool will be added to the KILLER project in the coming months so stay tuned up. Also ideas, bug reports, contributions are more than welcome !**

** Stay tuned : Follow me on twitter @ https://twitter.com/TH3xACE **

=============
Overview
=============

*SCREEN_KILLER* is a tool that can to take screenshot for a self-defined period (seconds) and also to log all terminal commands.

This means that you can take track of all commands run for whatever number of terminals you have.

* **Important: The tool for now is dev for only bash terminal. Will not work on ZSH,CSH...for now (if interested drop an issue).**

=============
Features
=============

Some of the functionalities 
--------------------------
* **Automated screen capture**
* **Commands logging**


=============
Usage
=============

Requirement: scrot must be installed (apt-get install scrot). Remember to chmod +x all .sh for execute right.

 .. code-block:: console
 
 	./screen_killer.sh 
   
  
It is recommended to run the tool as root but you can sudo ./screen_killer.sh .It should work but I have not tested all the features.
  
Then choose the feature that you want to run. It is important to stop the capturing at the end of the day. 
  
 * **Don't forget to stop capturing when you are done!**
 
 .. image:: ./pictures/sck.png
 	:width: 700px
 	:alt: Project
 
 .. raw:: html	
  
+----------------------------------------------------------+----------------------------------------------------------+
|* **Video 1 : Demo - Terminal Logging**	           |* **Video 2: Demo - Screenshot** 	                      |
|.. raw:: html						   |.. raw:: html					      |
|							   |							      |
|  <a href="https://youtu.be/AjCy7yep8I4">   		   |  <a href="https://youtu.be/hsyd9OUOgZo">   	      |
|  <img src="./pictures/sckv.jpg" width="350" height="200">|  <img src="./pictures/sckv.jpg" width="350" height="200">|
|  </a>							   |  </a>						      |
+----------------------------------------------------------+----------------------------------------------------------+


=============
Disclaimer
=============
This script is for Educational purpose ONLY. Do not use it without permission. The usual disclaimer applies, especially the fact that me (TH3xACE) is not liable for any damages 
caused by direct or indirect use of the information or functionality provided by these programs. The author or any Internet provider bears NO responsibility for content or misuse 
of these programs or any derivatives thereof. By using these programs you accept the fact that any damage (dataloss, system crash, system compromise, etc.) caused by the use of 
the script is not my responsibility.




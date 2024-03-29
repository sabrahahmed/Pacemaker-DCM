<h1> Pacemaker Device-Controller Monitor </h1>

<h2> Description </h2>
This application is associated with the 3K04 Software Development course at McMaster University.
<br/>
<br/>
This Device-Controller Monitor (DCM), built using Python, enables remote transmission of instructions and receipt of data from a pacemaker (developed by team in MATLAB Simulink). The DCM features an intuitive and user-friendly interface that supports up to ten simultaneous users who can log in, register, and interact with their pacemakers. 
<br/>
<br/>
<p align="center">
  <img src="https://user-images.githubusercontent.com/108163033/224840056-168aa7c9-f693-4fa4-83a5-26486ce863a0.png" width="700"/>
</p>

Upon logging in, users can easily customize their pacemaker settings across four pacing modes and visualize live heart electrogram data captured via PySerial (serial communication) and plotted using Python's Matplotlib library.

<p align="center">
  <img src="https://user-images.githubusercontent.com/108163033/224839931-ad75c1d4-d394-4cfa-b2f9-98dd50f53098.png" width="700"/>
</p>

Users can also sign-out or choose to delete their account. 

<p align="center">
  <img src="https://github.com/sabrahahmed/Pacemaker-DCM/assets/108163033/fb48cab9-9404-4172-b312-ae90ff1ae7e5" width="700"/>
</p>


<h2> Installation and Usage </h2>
NOTE: this application is meant to be connected to a Pacemaker device to use all features. To run the application, you will need to install Python 3.6 or above and pull the project from github to a local repo. Afterwards, open the project in a code editor of your choice (e.g. PyCharm). You will need to install the following libraries in your terminal to run the project: 
<br/>
<br/>

1. Install PySimpleGui
```Bash
pip install pysimplegui
```

2. Install PySerial
```Bash
pip install pyserial
```

3. Install Matplotlib
```Bash
pip install matplotlib
```

<h2> Technologies Used </h2>
<ul>
    <li>Python </li>
    <li>SQlite </li>
    <li>PySimpleGui</li>
    <li>Matplotlib</li>
    <li>PySerial</li>
    <li>Pacemaker Device</li>
</ul>












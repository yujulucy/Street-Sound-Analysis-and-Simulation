# Street-Sound-Analysis-and-Simulation

### Instructions to start:
Start a simple http server with Python.
1) Start cmd.exe and navigate to the folder you downloaded/cloned

2) For <b>python2</b>, type:
```
python -m SimpleHTTPServer 8080
```
For <b>python3</b>, type:
```
python -m http.server 8080
```
When it is started, you will see the message: 
```
Serving HTTP on 0.0.0.0 port 8080 ...
```

3) Now open a browser and type the address: http://127.0.0.1:8080/home.html. You can also access it with http://localhost:8080. You can start by accessing home.html.


### Main Files
This project consists of 3 main webpages (home.html, start.html, and analysis.html).  

#### home.html:
- General homepage for the whole project  

#### start.html:
This webpage is displayed when "Street View" on the sidebar is clicked.
Currently, not all locations have displays from all timings shown in the choices.
![instr1](https://user-images.githubusercontent.com/12662268/37923498-d8b1eb26-3161-11e8-8faf-bc0f9a1c6c97.png)

#### analysis.html:
This webpage is displayed when "Data" on the sidebar is clicked.
Displays information of data collected and used in this project (panorama and audio files).
Table of panoramas are also included here (the ticks show the panoramas available for testing)
![chart](https://user-images.githubusercontent.com/12662268/37923876-d93031d8-3162-11e8-8bf0-2c71a9869f96.png)

#### Similar Projects (found in the any of the 3 webpages above):
- Sounds of Street View
- Sound City Project
- Pregoneros de Medellín

#### Download Source (found in the any of the 3 webpages above):
- Leads to this github site to download the scripts for this project  

### Data Collected
Data.docx:
- Keeps track of the panoramas taken  
- Contains information such as the position of the panoramas are taken and the recordings made

### Testing script
index.html:
- A webpage displaying only the street view without links to any other pages  

### Screenshots of Routes from Tampines MRT Station to Round Market
#### General Route
Red, green, orange, and blue lines indicate the available paths.
Circle marks the destination (Round Market)
![routes](https://user-images.githubusercontent.com/12662268/37922309-cd2433b6-315e-11e8-89d0-fbc0eed95dd0.png)

#### Parts of Routes
Red spots indicate the positions available for testing.

Route (1/4)
![route_part1](https://user-images.githubusercontent.com/12662268/37921647-ffde937a-315c-11e8-929a-a8e02bde3c44.png)

Route (2/4)
![route_part2](https://user-images.githubusercontent.com/12662268/37921673-0f2c02d6-315d-11e8-881e-86a11713c120.png)

Route (3/4)
![route_part3](https://user-images.githubusercontent.com/12662268/37921690-1a3ec37a-315d-11e8-8770-3174558afa4a.png)

Route (4/4)
![route_part4](https://user-images.githubusercontent.com/12662268/37921698-1ce77b80-315d-11e8-969b-177cd771d81f.png)

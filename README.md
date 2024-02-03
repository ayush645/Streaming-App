
  <h1><p align="center"><b><b>Playing Livestream</b></b>
</p></h1>

<div align="center">

  <a href="">![Website shields.io](https://img.shields.io/website-up-down-green-red/http/shields.io.svg)</a>
  <a href="">![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)</a>
  <a href="">![Open In Collab](https://colab.research.google.com/assets/colab-badge.svg)</a>
  <a href="">[![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)](https://www.python.org/)</a>
  <a href="">[![Minimum node.js version](https://badgen.net/npm/node/express)](https://npmjs.com/package/express)</a>
</div>

<p align="Center"><a href="https://streaming-live-henna.vercel.app/" > 🌐 Visit Me Now 🌐</a></p>


## Understanding Problem Statement

Playing Livestream: The app should be able to play a live stream video from a given RTSP URL. Users should have basic controls such as play, pause,and volume adjustment.
1. Overlay Options: Users can add custom overlays
(such as logos and text) on top of the livestream. These overlays can be positioned and resized as needed.
2. CRUD API for Overlays and Settings:
•Create: Users should be able to create and save custom overlay
settings, including position, size, and content.
•Read: Users should be able to retrieve their saved overlay settings.
•Update: Users should be able to modify existing overlay settings.
•Delete: Users should be able to delete saved overlay settings.


## Tech Stack Used

![image](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![Render](https://img.shields.io/badge/Render-%46E3B7.svg?style=for-the-badge&logo=render&logoColor=white)
![NPM](https://img.shields.io/badge/NPM-%23CB3837.svg?style=for-the-badge&logo=npm&logoColor=white)
![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)




### Install packages or API:

```
$ pip install -r requirements.txt
```

### Start Local Server For API Testing:

```
$ python 
```

For Testing The API different ways can be used either you can download PostMan Community Version for testing. Once you start the local server just add a route "\predict" at the end of your local host link. It might look as well

```
$ https:\\{Your IP}\predict
```

It requires a header which contains different details which will be given as user input via website and these will be used to predict the possiblity of fraud or not-fraud. A sample header which might look as follows:-

```
{
    "NPPM": 1,
    "LoanStatus": "existing loans paid back duly till now",
    "Objective": "Purchase of radio/television",
    "Amount": 1278,
    "Guarantee": "none",
    "Experience": "between 1 and 4 years",
    "M_Status": "male and single",
    "ExistingLoan": 1,
    "Age": 36,
    "CA_Balance": "no current account",
    "SA_Balance": "less than 100",
    "PI_Balance": 4,
    "WorkAB": "Yes",
    "PhNum": 0,
    "Tenure": 24,
    "prop": "Real Estate",
    "JobTyp": "management/ self-employed/highly qualified employee/ officer",
    "HouseT": "own",
    "NOE": 1
}
```


### Start Website on LocalHost For Testing:

Pre-requiste you should have node installed and setup complted on your system to run AILOEC on your local system 

```
$ npm install root_dir/main_dir
```

```
$ npm run dev
```

# SoundGenerator
March - May 2025 <br>

Web-based Sound Generator that creates a downloadable cartridge. Made as a project work. <br>
This proect includes the data analysis of the complete dx7 voice sets. <br>

## Authors: <br>
Reea Rinnemäki - frontend & backend programming, testing <br>
Noora Nevalainen - collecting datasets, cleaning data, data analytics, python programming, testing <br>
Joel Hämälainen - frontend programming and testing <br>


## Built with: <br>
Backend: Python <br>
    -fastapi uvicorn <br>
Frontend: React + JS <br>

## Installation: <br>
Needed:  <br>
Git <br>
Node (created with  v22.14.0) <br>
npm <br>

Download this repo <br>
in frontend folder, in cmd run:<br>
'npm install', then 'npm run dev' <br>

## HOW TO USE <br>

**Open frontend:** <br>
in SoundGenerator/frontend  => npm install <br>
then: npm run dev <br>
follow link

**Backend portion is not usable at the moment** <br>
**Connect backend to frontend:** <br>
1 -open cmd in root, create venv(python -m venv venv) <br>
or activate it (venv\Scripts\activate) <br> 

2 -go to BACKEND dir <br>
NOTE this needs to be done only when first using venv or when req. has been updated!<br>
open cmd and run in venv: pip install -r requirements.txt <br>
Updating requirements.txt in backend dir terminal: pip freeze > requirements.txt

3 -in terminal: uvicorn api:app --reload <br>
OR if you know the port: <br>
uvicorn api:app --reload --port XXXX <br>

## DATA ANALYSIS <br>

Separate data analysis section is in /dx7_analysis folder. <br>
Instructions how to use the analyzer is in the same folder. <br>
Also holds the final report from analyzing all the DX7 sound files. <br>

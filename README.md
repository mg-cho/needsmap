# Needs Map
**Womxn Hacks 2020**

*Devpost: https://devpost.com/software/needsmap*

## Contributors:

Idea, main app, Google Maps API : sihra

Google Maps API, main app, UI, logo, design & branding: mg-cho

UI & registration/login: Keerthana-coder19

Database: 3ri5


## Inspiration
With over 53,000 people in Los Angeles County living without a home, there is a clear epidemic of homelessness in LA. Although many wish to help, the actions that one could take to assist are unclear. Thus, the needs of homeless shelters go unmet. We believe there is a sore need today for a service to facilitate more effective communication and bridge the gap between shelters and donors.

## What It Does

NeedsMap offers two services. The first is for shelters: We offer a registration process for shelters, which gives them a marker on our map and a way to upload what they need and how much they need it.

The second service is for those who want to help. Our interactive Google map shows the viewer the locations of homeless shelters across the county. When one clicks on a marker, they can view the shelter's information, the resources it needs, and how badly it needs each one. In this fashion, not only do we let donors know how to help, we give them a way to give each shelter what it needs most - making their aid the most effective it can be.

# How to Run NeedsMap

1) Download & install python 3.7 and virtualenv

2) Create virtualenv in desired directory with
>python3 -m venv [path to desired directory]

3) Activate venv
>venv\Scripts\activate

4) Install requirements
>pip install -r requirements.pip

5) Link flask to app
>C:[path to directory where your app is]>set FLASK_APP=[app file name]

5) Run application
>flask run

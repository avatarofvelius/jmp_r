<!--  Data: \www\htdocs\_data\obsidian\obsidian\Archive -->

# J[u]MP

___

## Reimplementation
Initial Project Was Overly Complicated, Without Understanding How Impractical It Would Be To Implement And Host. Initially Planned On Running A Complicated Backend On A Local Machine And Serve JSON And Markdown Files Through A Flask API.

Instead Of Using An API, Simply Serving The JSON And Markdown Files And Merging or Updating When Required. This Simplified The Process, Nearly Eliminating The Need For A Dedicated Backend Service.

## Prerequisites

 > Finish PHP Course
1. Re Learn PHP

 > Wait For jQuery Release ( currently beta )
2. Re learn jQuery

 > Wait For Htmx 2 Release ( currently alpha )
3. Learn Htmx 

___

## Purpose
Serve Markdown Files From Local System To Online Archive Website.

1. Render Markdown On Screen With Parsedown.php

2. Dynamically Serve Collections of Markdown Files
    - Htmx Use Cases?
    - jQuery Use Cases? ( current )

3. PHP Micro Framework
    - Is A Framework Needed?
    - What Are The Benifits
    - Leaf PHP Use Cases

4. Pico.css For Simplicity

5. JSON
    - What Data Is Needed?
    - MD To JSON With Pandoc?
    - SQLite Database Instead? ( current )

6. What Is Needed In A SQLite Database



## Usage
- jQuery 4 Slim ( alpha - not implemented )
- Htmx 2 ( not released )
- sqlite 3 ( not currently needed )
- Parsedown.php


___


## Packages
- jQuery
https://blog.jquery.com/

- Htmx
https://htmx.org/docs/

- Leaf PHP
https://leafphp.dev/docs/introduction/

- SQLite
https://www.sqlite.org/whentouse.html

- Parsedown
https://parsedown.org/

- Pico CSS
https://picocss.com/docs/



___



# Old Repository
# R3D ( Offline Repository )
a flask backend, with a basic pico.css and alpine.js frontend.


## Purpose
Learning and implementing Flask with Celery automation, with an easily deployed light frontend.

1. simple flask backend with minimal admin, redis, and celery.
2. pico.css for nice looking css without frameworks. ( tailwind/bootstrap )
3. alpine.js for data injection and modern jquery features.

## Process
- initial version without redis, flask api, or backend automation.
1. celery service workers manage local data, ending up as json objects for frontend.
2. flask serves data locally as an api, through redis, or pushed physically to host.
3. alpine or other alternative to inject json to frontend. 


## Experimental & Situational Processes


### Redis
https://redis.io/docs/getting-started/installation/install-redis-on-windows/
- redis not easily supported on windows.
- do not want to install linux through WSL. 

- install redis on raspberry pi. use for celery workers amd nosql data objects.
1. use celery to automate background workers to send update data to redis. 
2. serve data as json objects via a Flask API.  


## Packages
- Flask
https://flask.palletsprojects.com/en/2.3.x/quickstart/

- Celery ( not implemented )
https://flask.palletsprojects.com/en/2.3.x/patterns/celery/

- Redis ( for celery service workers not implemented )
https://redis.io/docs/getting-started/

- Pico.css
https://picocss.com/docs/

- Alpine.js ( not implemented )
https://alpinejs.dev/start-here

- Petite-Vue ( alternative to Alpine.js )
https://github.com/vuejs/petite-vue



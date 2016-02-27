# Free-Hosting
Follow below instruction for hosting your website

Go to https://cloud.google.com/appengine/downloads

Download SDK for Python as per your operating system

clone repository(https://github.com/JINDALG/Free-Hosting.git) or download zip file

Create folder named "website" and place all downloaded file in it.

replace the index.html with your website files

rename your html file as index.html

place this folder into googleappengine folder (where your SDK install)

open the url https://cloud.google.com/ and click on my consol (top right corner)

create new project.

go to googleappengine folder in terminal/cmd

run the following command 

appcfg.py -A <YOUR_PROJECT_ID_> update website/

your website is now hosted to see your website open 

http://your-app-id.appspot.com/


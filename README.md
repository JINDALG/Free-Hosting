# Free-Hosting
Follow below instruction for hosting your website

Go to https://cloud.google.com/appengine/downloads

Download SDK for Python as per your operating system

clone repository(https://github.com/JINDALG/Free-Hosting.git) or download zip file

Create folder named "website" and place all downloaded file in it.

Go to Template folder and relace index.html file with your website's file

Rename your main html file with index.html

place this(website) folder into googleappengine folder (where your SDK install)

Go to https://cloud.google.com/ and click on my consol (top right corner)

Create new project.

After creating project a project id will be generate.

Go to googleappengine folder in terminal/cmd

Run the following command  appcfg.py -A <YOUR_PROJECT_ID_> update website/

your website is now hosted to see your website open 

http://your-app-id.appspot.com/

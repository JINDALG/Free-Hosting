# Free-Hosting
It is a module which can host your website free.

https://cloud.google.com/appengine/downloads open this link
download SDK as per your operating system
clone this repository and unzip files
place the file in a folder named "website".
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


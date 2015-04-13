###### install tortoise git at end
#`Guide For Noobs` - For Windows Users
######Hopefully this will fix some headaches! It took me ages to figure out how to fx things and get it all running by using many, many forums.
##Ruby
1. `C:\Ruby22` (Better to install at C)
2. add ruby executables
3. associate files
#####INSTALL DEVKIT
    1. extract to `C:\devkit` (Better to install at C, can be anywhere though)
    2. open "Start Command Prompt with Ruby"
    3. `cd C:\devkit` (change to the location where you extracted it)
    4. from `C:\devkit` (or where you extracted it)
        1. `ruby dk.rb init` (will create files)
        2. `ruby dk.rb review` (see if ruby path is in .yml file. Example `C:\Ruby22`)
        3. `ruby dk.rb` install

    5. `gem install json` (test if working and all is set up)
   ###### *EVENTMACHINE PROBLEM FIX*
   - `gem install eventmachine -v 1.0.4` 
   - Seemed to fix it. Plenty of help on google if not. Anything else missing just install them.
    
NODE.js
git 1.9.5
use from windows cmd
checkout windows style

######CREATE THEME IN CUR DIR
dugway create "theme-name-within-this"
RUN SERVER "theme-name" DIR
cd theme-name/
dugway server

*Keep CMD running to keep server running. Local server "like node"*
127.0.0.1:9292

##FOUNDATION FOR APPS
1. `git clone https://github.com/zurb/foundation-apps-template.git appName`
2. `cd appName`
3. `npm install`
4. `bower install`
5. `npm start` (compile the Sass and assemble your Angular app. 
6.   * Now go to `localhost:8080` in your browser to see it in action.** When you change any file in the `client` folder, the appropriate Gulp task will run to build new files.)
npm start build (builds without server)
if files are missing change gulpfile
### WEB DEV
Grunt (pop, learn first)
Gulp (new/easier)
Github
bower package management

2) Learn Basic HTML/CSS/Javascript

No matter what direction you go, you have to learn the basics.  Currently, every browser runs 3 languages: HTML, CSS, Javascript.  Basic HTML can be learned very quickly and CSS/Javascript just take a little effort.  Even if you don’t become a CSS or Javascript ninja, you’ll need to know the basics of how it works, since it is one of the 3 primary browser languages.

3) Learn a couple of misc. development skills

Github (from the command line, not the application), knowledge of webservices, FTP, SSH, using the terminal.  These are skills that you need to know no matter what route you take.

4) Decide on a path – frontend or backend?

So, out of all of the things you’ve done so far, which is the most fun?  If you like CSS and design, then I recommend front-end development.  If you like using $.ajax and working with data, then maybe go backend.  Either way, you’re not committed – there’s no such thing as useless web knowledge, but what counts is learning one skill set very well rather than learning a bunch of skills a little bit.
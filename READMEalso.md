###### install tortoise git at end
RUBY
C:\Ruby22
add ruby executables
associate files

INSTALL DEVKIT C:\devkit
from C:\devkit run:
ruby dk.rb init
ruby dk.rb review 
	*Should be C:\Ruby22 dir*
ruby dk.rb install

gem install json
	*test if working if not try below...*
NODE.js
git 1.9.5
use from windows cmd
checkout windows style


EVENTMACHINE PROBLEM FIX
gem install eventmachine -v 1.0.4

CREATE THEME IN CUR DIR
dugway create "theme-name-within-this"
RUN SERVER "theme-name" DIR
cd theme-name/
dugway server

*Keep CMD running to keep server running. Local server "like node"*
127.0.0.1:9292

FOUNDATION FOR APPS
git clone https://github.com/zurb/foundation-apps-template.git appName
cd appName
npm install
bower install
npm start (compile the Sass and assemble your Angular app. **Now go to `localhost:8080` in your browser to see it in action.** When you change any file in the `client` folder, the appropriate Gulp task will run to build new files.)
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
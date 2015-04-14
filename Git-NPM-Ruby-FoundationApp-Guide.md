#`Git/NPM/Ruby/Foundation-App Guide ` - For Windows Users
######Hopefully this will fix some headaches! It took me ages to figure out how to fx things and get it all running by using many, many forums. Mainly for my own reference but might help others.
*Written by [DannnnB](https://github.com/DannnB)*
###### *Will Add More as I Go...*
##Ruby
1. `C:\Ruby22` (Better to install at C)
2. Add ruby executables
3. Associate files
##### INSTALL DEVKIT
4. Extract to `C:\devkit` (Better to install at C, can be anywhere though)
5. Open "Start Command Prompt with Ruby"
6. `cd C:\devkit` (Change to the location where you extracted it)
7. From `C:\devkit` (Location where you extracted it)
    1. `ruby dk.rb init` (Will create files)
    2. `ruby dk.rb review` (See if ruby path is in .yml file. Example `C:\Ruby22`)
    3. `ruby dk.rb` install

    5. `gem install json` (Test if working and all is set up)
    ###### EVENTMACHINE PROBLEM FIX
    * `gem install eventmachine -v 1.0.4` 
    * Seemed to fix it. Plenty of help on Google if not. Anything else missing just install them.
    
##FOUNDATION FOR APPS
1. `git clone https://github.com/zurb/foundation-apps-template.git appName`
2. `cd appName`
3. `npm install`
4. `bower install`
5. `npm start` (Compile the Sass and assemble your Angular app) 
6. `npm start build` (Builds without starting server)
7.  Should auto open a localhost tab in your default browser.
    * If not, go to `localhost:8080` in the browser 
    * Changes in the *Client* folder will start the gulp task and put files in the *build* folder
    * If files are missing change the gulpfile to add them. many other settings in here.
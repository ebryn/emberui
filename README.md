emberui
=======

Interface widgets for ember.js

Install
=======
0. Clone this repository `git clone https://github.com/jacojoubert/emberui.git && cd emberui`
1. [Install node](http://nodejs.org/)
2. Install grunt `sudo npm install -g grunt-cli` (or `npm install -g grunt-cli` if you are fancy)
3. Install bower `sudo npm install -g bower` (or `npm install -g bower` if you are fancy)
4. Check that you are in the emberui folder and then install this projects dependancies `npm install`. If you get errors, it is possible `sudo npm install` may work, but it is more likely you made a mistake earlier on in the process.
5. Start the server `grunt server`. This should start without issue, you should see the message that says "no errors", although there may be some red text that flies by you, just ignore it unless you cannot get the page to load.

Website
=======
1. We use a submodule for the website. Run `git submodule update --init` to enable submodules if doing this for the first time, although it never hurts to run it. Then in the module if you are setting this up for the first time, you will need to set the branch with `git checkout gh-pages`. 
2. Be aware that only `CNAME` and `404.html` are not auto-generated by grunt. To add more edit package.sh or talk to @zachaysan.
3. `bash package.sh` should run successfully. If you have changes it will automatically push them to the website repo. If it doesn't end with "Successfully built package" then something has gone wrong (this types of scripts are brittle.
4. Do a `git status` here and commit the changes to `website` to point to the new submodule.

Contributing
============

Contributions are welcome, but beware! This project maintainer's mind is full of madness and mania! He has planned features that must contain a full measures of grace and affordance. For all but those which are but definite bug fixes you would be wise to seek the master's guidance, lest ye fashion something that is left wanting.

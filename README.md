# evol-mean-cheatsheet
MEAN cheatsheet


NODE

////  Get Version
node --version && npm --version

////  Install a package globally, add -g flag.  leave off -g to install locally to current folder
npm install <packagename> -g


////  View what packages are installed globally
npm list -g --depth=0



BOWER

////  Install Bower globally
npm install bower -g

////  Install a Bower Package to your local directory and update bower.json dependencies  list 
bower install <packagename> --save




GRUNT & GULP

////  Install Grunt & Gulp globally - we'll probably just use Grunt tho
npm install -g gulp grunt-cli

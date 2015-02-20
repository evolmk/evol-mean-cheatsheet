# evol-mean-cheatsheet
MEAN cheatsheet


<strong>NODE</strong>

////  Get Version<br>
node --version && npm --version

////  Install a package globally, add -g flag.  leave off -g to install locally to current folder<br>
npm install <i>PACKAGENAME</i> -g


//// View what packages are installed globally<br>
npm list -g --depth=0



<strong>BOWER</strong>

////  Install Bower globally<br>
npm install bower -g

////  Install a Bower Package to your local directory and update bower.json dependencies  list <br>
bower install <i>PACKAGENAME</i> --save




<strong>GRUNT & GULP</strong>

////  Install Grunt & Gulp globally - we'll probably just use Grunt tho<br>
npm install -g gulp grunt-cli

git clone https://github.com/pyavchik/webdriverio-wdio.git
cd webdriverio-wdio
npm init -y
npm install webdriverio
node_modules/.bin/wdio 

? Where do you want to execute your tests? On my local machine
? Which framework do you want to use? mocha
? Shall I install the framework adapter for you? Yes
? Where are your test specs located? ./test/specs/**/*.js
? Which reporter do you want to use? 
? Do you want to add a service to your test setup? 
? Level of logging verbosity silent
? In which directory should screenshots gets saved if a command fails? ./errorShots/
? What is the base url? http://localhost

node_modules/.bin/wdio --path '/'

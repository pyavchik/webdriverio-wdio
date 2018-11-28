How to use:
```bash
git clone https://github.com/pyavchik/webdriverio-wdio.git
cd webdriverio-wdio
npm init -y
npm install webdriverio --save-dev
npm install wdio-selenium-standalone-service --save-dev
node_modules/.bin/wdio
```
Lets setup wdio: 

? Where do you want to execute your tests? On my local machine: "Enter"<br>
? Which framework do you want to use? mocha: "Enter"<br>
? Shall I install the framework adapter for you? : "Enter"<br>
? Where are your test specs located? ./test/specs/**/*.js : "Enter"<br>
? Which reporter do you want to use? : "Enter"<br>
? Do you want to add a service to your test setup?: "Enter"<br> 
? Level of logging verbosity silent: "Enter"<br>
? In which directory should screenshots gets saved if a command fails? ./errorShots/: "Enter"<br>
? What is the base url? http://localhost: "Enter"<br>

You need to add selenium-standalone to your service array:<br>
// wdio.conf.js<br>
```code
export.config = {
  // ...
  services: ['selenium-standalone'],
  // ...
};
```

Finally lets start test:
```bash
node_modules/.bin/wdio wdio.conf.js
```


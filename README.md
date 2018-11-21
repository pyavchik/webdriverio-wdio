How to use:
```bash
git clone https://github.com/pyavchik/webdriverio-wdio.git
cd webdriverio-wdio
npm init -y
npm install webdriverio
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

Finally lets start test:
```bash
node_modules/.bin/wdio --path '/'
```


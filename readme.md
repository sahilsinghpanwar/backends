note: '/' is used for home route

 step-1 use command npm init

step-2 package.json mai hum ek index.js ko run karane k liye ek script add karte hain
 "start": "node index.js"    use command ----> npm run start

step-3  use command (npm install express --sava)

step-4 express.js ke website se hum ek app ko create karte hain, or index.js mai put krte h.  (local server k liye)

step-5 two way for import in index.js using 1) common.js 2) module

step-6 hume package.json mai type bhi likne hoga common.js ya module

step-7 toh hum aab or bhi req handle krange  eg-- /twitter


note: res.send kai under hum kuch bhi bhej sakthe h eg-> h1 tag kai sath, json, cookies


step-8 install dotenv package command(npm install dotenv --save), create .env file.

add kro index.js mai ye 
require('dotenv').config()     (website per h   dotenv)
console.log(process.env)     or .env kai baad jo bhi file add krne ho usko . krke add krna hoga.

listen wale mai change hoga process.env.______ add krna hoga jo bhi .env file mai hoga eg--> PORT



step-9 abb ye ho gye production ready   aab hume esai production mai deploy krna hoga (eg-> aws, digital ocean) but this application is paid

step-10 pahle hum git mai push karnge sara code fir production mai deploy krange

step-11 git setup krange window per , fir new repository create karange, or give command ko chalange 
git init
 
 step-12 hum node_modules push ne krte github per kyuke ye hum ek command sai create kr sakhte h toh hum isko .gitignore mai rakhange.

 step-13 aab git add . command subhi folder , files ko git mai push krne k liye use krenge. koi ek files bhi add kr sakhte h 
 git add index.js use kr ke

 step-14 git commit -m first commit
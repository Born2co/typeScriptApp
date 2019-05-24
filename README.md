# typeScriptApp  open this folder in VS code
open terminal >npm init 
(this will give package.json)
add this..
 "scripts": {
    "start": "tsc && node out/index.js",
and run :>> npm start 

>tsc --init
(Successfully created a tsconfig.json file.)
create src folder 
 "rootDir": "./src",-> in tsconfig.json 
 
 create out folder 
 "outDir": "./out", 
.............................
Adding external lib
1 request liberary (request api )
>>npm install request lodash --save
npm install @types/request --save-dev
2 lodash(sorting the object)
npm install @types/lodash--save-dev

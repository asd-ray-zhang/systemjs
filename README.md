npm init -y  //initial npm project
npm install jspm --save-dev//install jspm

jspm install jq=jquery  //install jquery and map to jq.

下面是安装的jquery:
"jq": "npm:jquery@3.2.1",


{}里是要依赖的包。
"github:jspm/nodelibs-assert@0.1.0": {
      "assert": "npm:assert@1.4.1"
    },

system.js
map:  允许你为模块名创建一个别名，当你引入一个模块，模块名会被相应的值替换


运行：
npm install;
./node_modules/.bin/jspm install jq=jquery;
npm run lite-server;
 No newline at end of file

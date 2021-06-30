# npmjs.harlie.com

公司内部的 npm registry

## 使用步骤

```
1. 推荐使用nrm切换npm源
npm install -g nrm
nrm add harlie http://42.192.37.59:7001
nrm use harlie

3.  使用内部源
···NPM···
npm config set registry 42.192.37.59:7001

···CNPM···
cnpm config set registry http://42.192.37.59:7001

···YARN···
yarn config set registry http://42.192.37.59:7001

4. 安装模块
npm install @harlie/cnpm-test 
cnpm install @harlie/cnpm-test  
yarn add @harlie/cnpm-test 

```

# npmjs.harlie.com

公司内部的 npm registry

## 使用步骤

```
1. 使用内部源
NPM:
npm config set registry 42.192.37.59:7001

2. 推荐使用nrm切换npm源
npm install -g nrm
nrm add harlie http://42.192.37.59:7001
nrm use harlie
```



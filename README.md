## Electron + React Hooks + TS 实战开发：从 0 到 1 实现简历平台

### 开发

#### 0001 安装 electron

Q：会有安装完成后无法使用的情况
A：下载官网的二进制包失败，导致无法执行 electron
A：npm config set ELECTRON_MIRROR http://npm.taobao.org/mirrors/electron/

#### 0002 安装 React、Babel

```bash
npm install react@17.0.2
npm install react-router@5.2.0 react-router-dom@5.2.0 react-dom@17.0.2
```

##### babel

babel：[https://babeljs.io/docs/en/usage#overview]

```bash
npm install @babel/polyfill@7.12.1 --save
npm install @babel/core@7.14.3 @babel/cli@7.14.3 --save-dev
npm install @babel/preset-env@7.14.2 @babel/preset-react@7.13.13 @babel/preset-typescript@7.13.0 --save-dev

npm install @babel/plugin-transform-runtime@7.14.3 --save-dev
npm install @babel/plugin-transform-modules-commonjs@7.14.0 --save-dev
```

#### 0003 安装 webpack

```bash
npm install webpack@4.44.1 --save-dev
npm install webpack-cli@3.3.12 --save-dev
npm install webpack-dev-server@3.11.2 --save-dev
```

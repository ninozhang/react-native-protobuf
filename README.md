# react-native-protobuf

由于 protobuf.js 无法在 React Native 中直接使用，简化了下适应 React Native

# 声明

这个模块的代码完全来自于 Protobuf.js 项目：
GitHub: https://github.com/dcodeIO/protobuf.js
NPM: https://www.npmjs.com/package/protobufjs

由于 protobuf.js 目前依赖了 fs 和 path ，无法直接在 React Native 中使用，
所以将原项目中的相应代码移除，以便可以在 React Native 中使用。

## 移除的方法

### BuilderPrototype["import"]
移除 filename 处理逻辑

### Util.fetch
移除读取逻辑
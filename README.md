

## 环境配置

1. 调试

- expo (安装expo之后就可以扫码调试，确保手机和电脑在同一个局域网中（即前三位的Ip需保持一致）,调试体验一般)。

- 模拟器（推荐genymotion,确保android sdk的安装（android studio））

  环境变量的配置：必须确保项目中使用的，$ANDROID_HOME的系统环境变量（通常也是项目默认使用的）,genymotion使用的sdk路径保持完全一致。

- 真机调试：保证上面环境配置正确的同时，让你的手机开启USB调试模式即可。



## Development

### redux, react-redux

- redux-persisit => state持久化
- redux-saga => redux effect
- seamless-immutable => state 的imutable
- reduxsauce => 减少redux样板代码

### react-native

- react-navagation => 路由库
- react-native-vector-icons => 图表库
- react-native-i18n => 国际化
- react-native-animatable => 动画
- apiSauce => 基于fetch的二次封装
- react-native-elements => react-native UI库
- storyBook => out of box的开发测试helper

## Issues

- [x] 上方被安卓的导航条遮住的问题(在expo配置中添加androidStatusBar解决问题)
- [x] 热更新报错的问题(在replaceReducer中添加persistReducer)
- [ ] StatusBar切换页面时感觉颜色切换没有和页面融合一体，体验不好，寻找更好的解决方案












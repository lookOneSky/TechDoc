## PicoAPI问题

### 手势识别PreView无效
手势识别在编辑器中无法Preview，需要启动Pico

### 手势识别Pico中只有手柄没有手
打包之后只有手柄问题
手握住了手柄手就出不来手了
另外手要过一会儿出来，且不能遮挡眼镜

### Pico中相机位置不对
出现原因和蓝图编译错误有关，需要重新创建蓝图Actor。
相机不能直接放在RootComponet上，需要嵌套一个SceneComponent


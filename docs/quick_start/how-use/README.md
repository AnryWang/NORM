# ORM组件使用说明


### 0. 组件结构说明

![项目架构](./../../_images/pro_arch.png)

### 1. 组件使用说明

#### 1.1 编译组件库

* 获取源码;
* 在QtCreator中打开NORM.pro, 不要选择影子构建，开始编译构建;
* 同级目录中会出现bin文件夹,里面就是编译好的组件库, 注意看版本信息;
* 在外部项目使用时直接把编译好的库和inc文件夹下的文件打包使用即可;
* 在内部项目使用时,请直接引用NORM_inc.pri即可,同时需要手动把编译好的库拷贝到主程序执行目录,或者编写辅助脚本在运行前拷贝;

#### 1.2 运行测试用例

* 编译并运行 example 子项目即可，不要勾选在终端运行;




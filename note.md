## 框架 angular bootstrap
我们写好代码，框架帮我们调用,强约束按照人家的规范来写代码。

## 库 react vue jquery
我们调用库中的方法，我们是主动的

## angular MVC MVVM 简化代码，提高了开发效率
### MVC
- model(数据)
- view (视图)
- controller (控制器)

> 单向，用户改变视图(表单元素)，更改后会触发控制器，获取数据后，在刷新视图

## 双向数据绑定
- model
- view
- viewModel (视图模型)

> 页面变化（表单元素），会触发数据的变化,数据的变化，会更改页面的变化

## 安装angular
### 全局安装（在命令行使用的）
```
npm install babel -g 
npm install bower -g 
```
### 本地安装（在代码里使用的）
```
npm install jquery
npm install angular
```

> npm是基于node，安装node后会直接安装npm,安装模块到node_modules文件夹下，如果当前没有会像上一级找

## 安装前生成package.json文件
```
npm init -y
```

> 默认安装angular1.0,市面1.5.8

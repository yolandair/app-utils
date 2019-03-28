# 判断客户端的一些信息组件

## Install

`npm install @cnpm/app-utils`

or

`<script type="text/javascript" src="http://n3.static.pg0.cn/fp/app-utils/dist/app-utils.js">`

## Usage

`在js中需要使用此组件获取客户端相关信息的时候进行调用`

## Example

[app-utils](http://front.chinaso365.com/fp/app-utils/example/index.html)
## Options


## Methods

### AppUtils.androidClient()  //当返回值为true时是安卓的客户端
### AppUtils.iosClient()      //当返回值为true时是ios的客户端
### AppUtils.clientType()     //返回值是"android"或者"ios"
### AppUtils.wechatClient()   //返回值是true是在微信打开  
### AppUtils.appClient("BeautifulChina")      //传入UA的值，如果返回true就是在当前的客户端
### AppUtils.isMobile();   //返回值是true代表是手机端访问
## Events

## 0.0.1

* 初始化 app-utils 组件

## 0.0.2

* 添加是否是移动端的判断函数 

## 0.0.3

* 修改readme

## 0.0.4

* 修改readme

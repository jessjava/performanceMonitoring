# performanceMonitoring 网页性能监控

## 说明

* 用到了window.performance属性监控网页的白屏时间、首屏时间、用户可操作时间、domready加载完成时间
* 支持发送到服务器作为日志（nginx）


## 浏览器支持情况
* IE：IE9以上支持，接口为window.msPerformance；
* chrome6-9：window.webkitPerformance
* chrome10：window.performance
* Firfox：firfox7.0以上支持，接口为：window.msPerformance
* Safari：接口为window.performance
* 移动端：window.webkitPerformance
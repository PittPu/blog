hexo本地正常显示，上传到github后没有样式

原因是_config.yml中配置的URL错误，在浏览器开发者模式中进行调试，找到URL和root的正确设置：
URL:https://pittpu.github.io/blog
root:/blog
部署后有一定时间的延迟。

# mugu‘s blog

##### 地址：<a href="https://www.bukun.top/">mugu's blog<a>

###### 原作

https://github.com/fluid-dev/hexo-theme-fluid

博客地址：https://rook1e.com/

------

###### 已解决

- ​	deploy后域名配置失效（2020\2\7）
  ​	原因：自动CNAME文件被自动删除

  ​	解决： 1.在本地的文件上添加CNAME后再deploy

  ​				 2.在根目录的_config.yml中找到deploy设置项；

  ​					在后面添加一行： delete :  false
  ​					(未验证，可自行尝试)

  ​	参考：https://github.com/hexojs/hexo/issues/2446
  
- 公共cdn (2020\2\7)

  - 七牛云cdn: https://www.staticfile.org/
  - 更换常用的库使用公共cdn加速网页

------

###### 待解决

- 图片加载问题 [加载缓慢]
- cdn加速优化（全局设置）[未设置]
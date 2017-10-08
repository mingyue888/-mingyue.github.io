<h3 style="#0366D6">隐式跳转 预览 <a href="it365.pw" >it365.pw</a></a></h3><br />
利用GitHu做页面跳转,
向你的 Github Pages 仓库添加一个CNAME(一定要*大写*)文件
现在国内的博客都不支持绑定顶级域名了，大多给你一个类似于xx.com/dd/的网址，让你域名cname都没有地方，查了下资料，找到了url隐藏转发的方式，代码实现如index.html
把index.html，放到github你创建的“用户名.github.io”项目里（不明白请百度github项目主页的设置方法），接着在github项目cname文件里绑定你的顶级域名，dns里设置cname到"http://用户名.github.io"上即可。

     这样设置完了，url是不会变动的，好像还有改进的方法，就是用“#”标记文章地址，用js控制读取url访问，我再琢磨下。。。

     ---------

        frameset好像是不能跨域名调用的吧？那样的话就只能这样子了.....

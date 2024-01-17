## 说明
1. 在原来 [rayder](https://github.com/devanshbatham/rayder) 项目基础上做了一点细微的修改，基于 docker 实现自动化，[详情](https://ayuxy.github.io/zh/tools/2023-1120-01/)
2. Linux 下使用 ./rayder_dev -w workflow.yaml file=input.txt 即可
3. 直接把测试的域名、url等放入指定文件即可
4. 如果直接使用提供的 yaml 模板必须配置 slack 的 webhook url，实际就是 [notify](https://github.com/projectdiscovery/notify#references) 项目里面 slack 的配置，具体如何配置可以参考 [slack webhook url 取得方法](https://juejin.cn/s/slack%20webhook%20url%20%E5%8F%96%E5%BE%97%E6%96%B9%E6%B3%95)，也可以谷歌自行搜索
5. 指纹识别仅匹配到漏洞后才会推送消息

### 文件清单说明
- registry.conf seata服务端配置 注册中心和配置中心的文件（现在默认注册中心和配置中心为nacos）
- nacos-conifg.sh,conifg.txt 由于我们使用nacos的配置中心，我们初始化的时候需要读取配置，这个脚本配置config.txt文件 将conifg.txt里面的配置上传到nacos配置中心
- docker-compose.yml docker-compose 启动文件 
# 注意事项

1. 保证启动顺序，虽然写在了docker-compose里，但还是推荐一个一个启动，否则很有可能直接挂了
2. 每次重启之前需要删掉volume，旧数据可能直接会挂
3. 具体我也不是太清楚，宿主机读取配置，其他不读取配置可以拉通

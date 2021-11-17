### 改进项目 ###
1. 使用 `actions/cache@v2` 替代 `commit` 保存新的 `REFRESH_TOKEN`
1. 同时将新的`REFRESH_TOKEN` 保存到 `artifact`

### 设置方式 ###
依次点击上栏Setting > Secrets > Add a new secret，新建 secret：

  内容分别如下: ( 把你的应用id改成你的应用id , 你的应用机密改成你的机密，单引号不要动 )
  
  - CLIENT_ID：`你的应用id`
  - CLIENT_SECRET：`你的应用机密`
  - REFRESH_TOKEN：`你的REFRESH_TOKEN`
  
### 更新`REFRESH_TOKEN` ###
  TODO

  
### Thanks ###
* https://github.com/wangziyingwen/AutoApiSecret

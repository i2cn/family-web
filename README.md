# 步骤

1. ## 切换淘宝镜像：

  ```bash
  npm install -g cnpm --registry=https://registry.npm.taobao.org
  ```

2. ## 以管理员权限运行cmd

3. ## 安装依赖：

  ```bash
  cnpm  install
  ```

4. ## 如果报错，执行下面命令，然后 cnpm install再安装：

  ```bash
  npm install --save node-sass --registry=https://registry.npm.taobao.org --disturl=https://npm.taobao.org/dist --sass-binary-site=http://npm.taobao.org/mirrors/node-sass
  ```

5. ## 如果之前安装失败，先清理缓存：

  ```bash
  npm rebuild node-sass
  npm uninstall node-sass
  ```

  




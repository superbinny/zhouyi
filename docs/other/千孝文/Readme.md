# <center> 发布方式
## 首先更新源码：

```
git push ......
```
## 登录服务器，运行以下命令：

```
cd Source/zhouyi/
source ./.venv/bin/activate
git pull
mkdocs build
rm ~/www/html/zhouyi/ -rf
mv site/ ~/www/html/zhouyi
```

# 发布方式

## 登录服务器，运行以下命令：

```
cd Source/zhouyi/
source ./.venv/bin/activate
git pull
mkdocs build
rm ~/www/html/zhouyi/ -rf
mv site/ ~/www/html/zhouyi
```
# 【打破信息差】萌新认识与入门算法竞赛 - wiki

## 环境搭建

推荐使用 conda 搭建环境。

首先创建虚拟环境

```shell
conda env create -f xcpc-wiki-env.yaml
```

激活环境

```shell
conda activate xcpc-wiki-env
```

## 更新

### 本地预览

```sh
mkdocs serve
```

然后打开浏览器输入`http://127.0.0.1:8000/`实时预览最终效果。

### 推送到 github 

```shell
mkdocs gh-deploy
```
# My Personal Website

[![actions](https://github.com/HaiyiMei/haiyi-mei.com/actions/workflows/deploy.yaml/badge.svg)](https://github.com/HaiyiMei/haiyi-mei.com/actions)

## Theme

https://github.com/haiyimei/hugo-profile

(forked from https://github.com/gurusabarish/hugo-profile)

## Build locally

### Clone

```bash
git clone git@github.com:HaiyiMei/haiyimei.github.io.git --recursive
```

### Requirements

- [hugo](https://gohugo.io/installation/)

```bash
sudo apt install hugo
# or
brew install hugo
```

### Edit

- [config.yaml](config.yaml)

### Preview

```bash
hugo server --disableFastRender
```

### Build static files

```bash
hugo --gc --minify --baseURL haiyi-mei.com
```

![gif](/albumartwork.gif)
> inspired by Apple’s macOS  inbuilt iTunes Screensaver

# MusicBrainz 收藏夹封面

### 1. [单个收藏夹](https://album-artwork.vercel.app/?id=8ac56a60-c667-4603-817e-793f0d2600b8)
`
https://album-artwork.vercel.app/?id=8ac56a60-c667-4603-817e-793f0d2600b8
`

### 2. [多个收藏夹](https://album-artwork.vercel.app/?id=8ac56a60-c667-4603-817e-793f0d2600b8&id=8bd472fd-b961-4c59-95f1-26521b072a63)
`
https://album-artwork.vercel.app/?id=8ac56a60-c667-4603-817e-793f0d2600b8&id=8bd472fd-b961-4c59-95f1-26521b072a63
`
## 示例源收藏夹：
https://musicbrainz.org/collection/8ac56a60-c667-4603-817e-793f0d2600b8
https://musicbrainz.org/collection/8bd472fd-b961-4c59-95f1-26521b072a63


# 本地封面

## 简介

本地模式允许您直接使用本地 `/cover` 目录中的图片文件作为专辑封面，无需依赖 MusicBrainz。

## 使用方法

0. 在本地运行 Python 服务器:  `python -m http.server 8000`

1. 在浏览器中访问: http://localhost:8000?local

2. 将您的专辑封面图片文件放置在网站根目录下的 `/cover` 文件夹中

3. 系统会自动扫描该目录下的所有图片文件（支持 jpg, jpeg, png, gif, webp, bmp 格式）

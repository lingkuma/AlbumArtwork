![gif](/albumartwork.gif)

> inspired by Apple’s macOS  inbuilt iTunes Screensaver

# MusicBrainz Collection Cover Art

### 1. [Single Collection](https://album-artwork.vercel.app/?id=8ac56a60-c667-4603-817e-793f0d2600b8)
`
https://album-artwork.vercel.app/?id=8ac56a60-c667-4603-817e-793f0d2600b8
`

### 2. [Multiple Collections](https://album-artwork.vercel.app/?id=8ac56a60-c667-4603-817e-793f0d2600b8&id=8bd472fd-b961-4c59-95f1-26521b072a63)
`
https://album-artwork.vercel.app/?id=8ac56a60-c667-4603-817e-793f0d2600b8&id=8bd472fd-b961-4c59-95f1-26521b072a63
`
## Example Source Collections:
https://musicbrainz.org/collection/8ac56a60-c667-4603-817e-793f0d2600b8
https://musicbrainz.org/collection/8bd472fd-b961-4c59-95f1-26521b072a63


# Local Cover Art

## Introduction

Local mode allows you to use image files directly from the local `/cover` directory as album covers, without relying on MusicBrainz.

## Usage

0. Run a Python server locally:  `python -m http.server 8000`

1. Visit in browser: http://localhost:8000?local

2. Place your album cover image files in the `/cover` folder in the website root directory

3. The system will automatically scan all image files in this directory (supports jpg, jpeg, png, gif, webp, bmp formats)
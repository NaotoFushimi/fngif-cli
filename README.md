# fngif-cli

very vimple script for convert movie to gif

## 自分用テスト
## private test script.

## Mac
```
brew install ffmpeg imagemagick
npm install -g fngif-cli
```

## Linux
```
apt-get install ffmpeg imagemagick
npm install -g fngif-cli

```

## Use
```
fngif-cli -i xxxxx.MP4 -s 30 -e 5 -f 10

-i  ...input file<string>
-s  ...start seconeds<int>
-e  ...capture time <int>
-f  ...framerate <int>
-c  ...resize <float>

```

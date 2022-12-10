<img src="https://github.com/REVENGE977/stremio-enhanced/raw/main/images/icon.ico" style="display: block;
  margin-left: auto;
  margin-right: auto;">
<h1 style="text-align: center;">[WIP] Stremio Enhanced</h1>

## What is stremio enhanced ?
basically a stremio client with plugins and themes support,
it runs the stremio streaming server and opens this [url](https://app.strem.io/shell-v4.4) in electron (i know its probably not the best way to do it, but thats just how i got it working).

with this project you can make stremio look like this:
![screenshot](https://github.com/REVENGE977/stremio-enhanced/raw/main/images/amoled_screenshot.png)

## Downloads
you can download the latest version from [here](https://github.com/REVENGE977/stremio-enhanced/releases)
or build it yourself
```
git clone https://github.com/REVENGE977/stremio-enhanced.git
cd stremio-enhanced
npm run package-win32
```

## Videos wont load ?
try this:
[download ffmpeg](https://github.com/BtbN/FFmpeg-Builds/releases/download/latest/ffmpeg-master-latest-win64-gpl.zip) and put it in the stremio-enhanced folder (you only need ffmpeg.exe, its in the bin folder).

## "Your code sucks"
i know, i dont have much experience with electron,
you're free to improve it and make a [pull request](https://github.com/REVENGE977/stremio-enhanced/pulls).


## Todo
might switch to [stremio web v5](https://github.com/Stremio/stremio-web)
## Table of contents
* [Download Video Codec SDK](#Download-Video-Codec-SDK)
* [Download FFmpeg](#Download-FFmpeg)
* [Download GLEW](#Download-GLEW)
* [Download freeglut](#Download-freeglut)
* [Run cmake](#Run-cmake)
* [Download Test Video](#Download-Test-Video)
* [Reference](#Reference)
  
## Download Video Codec SDK
https://developer.nvidia.com/video-codec-sdk

## Download FFmpeg
https://github.com/BtbN/FFmpeg-Builds/releases

The package name is ffmpeg-n4.4-latest-win64-lgpl-shared-4.4.zip

## Download GLEW
https://glew.sourceforge.net/

## Download freeglut
https://freeglut.sourceforge.net/

## Run cmake
"C:\Program Files (x86)\Microsoft Visual Studio\2019\Community\Common7\IDE\CommonExtensions\Microsoft\CMake\CMake\bin\cmake.exe" -G"Visual Studio 16 2019" -A"x64" -DCMAKE_BUILD_TYPE=Release -DFFMPEG_DIR=Video_Codec_SDK_12.1.14/ffmpeg -DGLUT_DIR=Video_Codec_SDK_12.1.14/freeglut -DGLUT_INC=Video_Codec_SDK_12.1.14/freeglut/include -DGLEW_DIR=Video_Codec_SDK_12.1.14/glew -DCMAKE_INSTALL_PREFIX=. ..

"C:\Program Files\Microsoft Visual Studio\2022\Community\Common7\IDE\CommonExtensions\Microsoft\CMake\CMake\bin\cmake.exe" -G"Visual Studio 17 2022" -A"x64" -DCMAKE_BUILD_TYPE=Release -DFFMPEG_DIR=Video_Codec_SDK_12.1.14/ffmpeg -DGLUT_DIR=Video_Codec_SDK_12.1.14/freeglut -DGLUT_INC=Video_Codec_SDK_12.1.14/freeglut/include -DGLEW_DIR=Video_Codec_SDK_12.1.14/glew -DCMAKE_INSTALL_PREFIX=. ..

## Download test video
   https://developer.nvidia.com/heavy-hand

## Reference
https://docs.nvidia.com/video-technologies/video-codec-sdk/12.1/read-me/index.html

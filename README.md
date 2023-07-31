# build_nvenc
1. download Video Codec SDK

   https://developer.nvidia.com/video-codec-sdk

2. download FFmpeg headers and libraries

   https://github.com/BtbN/FFmpeg-Builds/releases

   The package name is ffmpeg-n4.4-latest-win64-lgpl-shared-4.4.zip

4. download GLEW libraries and headers

   https://glew.sourceforge.net/

5. download freeglut libraries and headers

   https://freeglut.sourceforge.net/

6. run cmake

   "C:\Program Files (x86)\Microsoft Visual Studio\2019\Community\Common7\IDE\CommonExtensions\Microsoft\CMake\CMake\bin\cmake.exe" -G"Visual Studio 16 2019" -A"x64" -DCMAKE_BUILD_TYPE=Release -DFFMPEG_DIR=Video_Codec_SDK_12.1.14/ffmpeg -DGLUT_DIR=Video_Codec_SDK_12.1.14/freeglut -DGLUT_INC=Video_Codec_SDK_12.1.14/freeglut/include -DGLEW_DIR=Video_Codec_SDK_12.1.14/glew -DCMAKE_INSTALL_PREFIX=. ..

   "C:\Program Files\Microsoft Visual Studio\2022\Community\Common7\IDE\CommonExtensions\Microsoft\CMake\CMake\bin\cmake.exe" -G"Visual Studio 17 2022" -A"x64" -DCMAKE_BUILD_TYPE=Release -DFFMPEG_DIR=Video_Codec_SDK_12.1.14/ffmpeg -DGLUT_DIR=Video_Codec_SDK_12.1.14/freeglut -DGLUT_INC=Video_Codec_SDK_12.1.14/freeglut/include -DGLEW_DIR=Video_Codec_SDK_12.1.14/glew -DCMAKE_INSTALL_PREFIX=. ..

7. download test video
   https://developer.nvidia.com/heavy-hand

ref: https://docs.nvidia.com/video-technologies/video-codec-sdk/12.1/read-me/index.html

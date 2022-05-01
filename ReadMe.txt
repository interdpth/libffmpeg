ffmpeg process
build via msys2
make nuget with files
build ffmpeg against libs and source headers in vs
done



https://github.com/Microsoft/Windows-classic-samples/tree/main/Samples/Win7Samples/multimedia/directshow/baseclasses build the sln and link

Vfw32.lib;Mfuuid.lib;Mfplat.lib;strmbasd.lib;Winmm.lib;Secur32.lib;Shlwapi.lib;Ws2_32.lib;Bcrypt.lib;libavutil.a;libswscale.a;libswresample.a;libavcodec.a;libavformat.a;libavfilter.a;libavdevice.a;kernel32.lib;user32.lib;gdi32.lib;winspool.lib;comdlg32.lib;advapi32.lib;shell32.lib;ole32.lib;oleaut32.lib;uuid.lib;odbc32.lib;odbccp32.lib;%(AdditionalDependencies)


for lib264  ./configure --disable-win32thread

for ffmpeg
pacman -Su mingw64
pacman -Syu
pacman -S tar make
 pacman -S mingw-w64-x86_64-toolchain

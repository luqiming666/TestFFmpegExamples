# TestFFmpegExamples
A windows console app to test example codes of FFmpeg.  
Tested with FFmpeg v7.1 in 2024.  

**How to run?**
1. copy example source file from FFmpeg\doc\examples
2. rename the main() in the example source .c file as xxx_main()
3. add the new xxx_main() to ffmpeg_examples_header.h
4. add some codes in TestFFmpegExamples.cpp to invoke xxx_main()
5. set Debug command-line parameters in Visual Studio when necessary

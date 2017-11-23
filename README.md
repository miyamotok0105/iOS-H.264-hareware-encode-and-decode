# iOS-H.264-hareware-encode-and-decode
Use the Video Toolbox for H.264 encoding

This demo implements H.264 hardware and hardware decoding. The source code for the video camera, debugging the best horizontal screen

1, click start button to start recording (the video encoding H.h264 into the sandbox, the file name: test.h264)

2, click the stop button to stop recording.

3, click the play button to play the video (test.h264 file read from the sandbox and decode play)

4, click stop to stop playing, clear the playback object


Sandbox test.h264 file can be connected to the computer through the device to open iTunes, select your own device, where you can find the first step to save the test.h264 source file

Copy the test.h264 file to your computer and rename it to .mov, which you can play directly with MPlayerX

By reference to the following blog, github demo and Apple's official information sorted out this set of H.264 encoding and decoding in a demo for your reference

Reference blog:

http://www.jianshu.com/p/a6530fa46a88

http://www.zhihu.com/question/20692215/answer/37458146

Apple's official reference:

WWDC2014 513 "direct access to media encoding and decoding"

Reference open source project:

https://github.com/stevenyao/iOSHardwareDecoder (Decode)

https://github.com/manishganvir/iOS-h264Hw-Toolbox (encoding)

This demo use Video Toolbox to encode / decode H264 video stream.

Compressing into H264, and decompress for CVPixelbuffer, using OpenGL to display. The video source come from camera. Recommending use landscape mode for this demo. (I do it on my ipad :)

1.Tap "start" button to begin capture video and decode video stream into H.264 format and save a file named: "test.h264" (file stream, raw H.264. Or you can save it as "xxx.mov "xxx.txt" whatever you want) in sanbox at the same time;

2.Tap "stop" button for stop capturing and stop encoding;

3.Tap "play" button to replay the video you just record in sanbox (decode H.264 stream).

4.Tap "Stop" button to stop decode.

You can get that file (test.h264) after those steps from iTunes: device -> "thisDemo" -> file shareing. Change the file subffix to ".mov". Drag into MPlayerX can play.

Refred:

https://github.com/stevenyao/iOSHardwareDecoder (decode)

https://github.com/manishganvir/iOS-h264Hw-Toolbox (encode)



# headless-jd2-docker-ffmpeg

if ffmpeg doesn't work, check the file `/cfg/org.jdownloader.controlling.ffmpeg.FFmpegSetup.json` ( in the config you bind to the docker image),
it must contain : 
```
{
  "binarypath" : "/usr/bin/ffmpeg",
  "binarypathprobe" : "/usr/bin/ffmpeg"
}
```
  

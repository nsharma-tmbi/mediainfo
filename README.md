# MEDIAINFO
***spring-boot-starter-parent ver. 1.5.3.RELEASE***
***java ver. 1.8***

This project demonstrated the capability of ffprobe (https://www.ffmpeg.org/ffprobe.html) for extracting format and codec details from a media file or URL.
ffprobe is a sub-project of ffmpeg open source project. ffmpeg is the gold standard for media parsing, transcoding and playback.

This project use another java open source project Jaffree (https://github.com/kokorin/Jaffree) which is a java wrapper for ffmpeg command line tools.

Usage
run with maven and pass the URL or filepath as parameter to extract it's media properties.
e.g ***mvn spring-boot:run -Drun.arguments=--mediaPath="https://tmbidigitalassetsazure.blob.core.windows.net/wpvideos/10 Kitchen Cabinet Storage Ideas Upgrades to Try.mp4"***


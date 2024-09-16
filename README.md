# MEDIAINFO
***spring-boot-starter-parent ver. 1.5.3.RELEASE***\
***java ver. 1.8***

This project demonstrated the capability of [ffprobe](https://www.ffmpeg.org/ffprobe.html) for extracting format and codec details from a media file or URL.

ffprobe is a sub-project of ffmpeg open source project. ffmpeg is the gold standard for media parsing, transcoding and playback.

This project use another java open source project [Jaffree](https://github.com/kokorin/Jaffree) which is a java wrapper for ffmpeg command line tools.

### MIME TYPE ###
A mime type (also known as a Multipurpose Internet Mail Extensions or MIME type) indicates the nature and format of a document. A MIME type most commonly consists of just two parts: a type and a subtype, separated by a slash (/). The type represents the general category into which the data type falls, such as video or text. The subtype identifies the exact kind of data of the specified type the MIME type represents. For example, for the MIME type video, the subtype might be mp4 (video/mp4), mpeg (video/mpeg) files.
Mome types for common image, audio and video files are listed below.

| Extension | MIME Type |
| --------: | :-------- |
| .aac | audio/aac |
| .apng | image/apng |
| .avif | image/avif |
| .avi | video/x-msvideo |
| .bmp | image/bmp |
| .gif | image/gif |
| .ico | image/vnd.microsoft.icon |
| .jpeg, .jpg | image/jpeg |
| .mid, .midi | audio/midi, audio/x-midi |
| .mp3 | audio/mpeg |
| .mp4 | video/mp4 |
| .mpeg | video/mpeg |
| .oga | audio/ogg |
| .ogv | video/ogg |
| .opus | audio/ogg |
| .png | image/png |
| .pdf | application/pdf |
| .svg | image/svg+xml |
| .tif, .tiff | image/tiff |
| .ts | video/mp2t |
| .wav | audio/wav |
| .weba | audio/webm |
| .webm | video/webm |
| .webp | image/webp |
| .3gp | video/3gpp; audio/3gpp if it doesn't contain video |
| .3g2 | video/3gpp2; audio/3gpp2 if it doesn't contain video |

## Usage ##
run with maven and pass the URL or filepath as parameter to extract it's media properties. e.g

`mvn spring-boot:run -Drun.arguments=--mediaPath="https://tmbidigitalassetsazure.blob.core.windows.net/wpvideos/10 Kitchen Cabinet Storage Ideas Upgrades to Try.mp4"`


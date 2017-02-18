# MobileVR
Generate 8 ball compatible x264 mp4 format video for MobileVR (native iOS and Android platforms)
* Track 0: Video (H264)
* Track 1: Stereo Audio (AAC)
* Track 2: Stereo Audio (AAC)
* Track 3: Stereo Audio (AAC)
* Track 4: Stereo Audio (AAC)

Under Mac or linux, make sure FFMPEG is fully installed, then execute
* ./convert [video file name] [front perspective wav file name] [left perspective wav file name] [back perspective wav file name] [right perspective wav file name] [video rotation offset clockwise] [output video file name]

=====================================================================

# WebVR
Generate 8 ball compatible vp8 webm format video for WebVR
* Track 0: Video (VP8)
* Track 1: 8 channels Audio (Opus)

Under Mac or linux, make sure FFMPEG is fully installed, then execute
* ./convert [8 channels wav audio file] [video file name] [output video file name]

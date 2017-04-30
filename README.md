**How Start?**

Edit file `start.sh` change a variable `YOUTUBE_KEY` on your key.
Start `start.sh`
Done!!!

*******

**Options**

`sh ./script.sh "set audio sampling rate (in Hz)" "input Set the number of audio channels" "Set the frame size" "YOUTUBE_KEY"`


**More option**

//fps
`-r 00`

// screen size
`-s 000x000`

// input file url
`-i`

// Force input or output file format. The format is normally auto detected for input files and guessed from the file extension for output files, so this option is not needed in most cases.
`-f`

// set audio sampling rate (in Hz)
`-ar`

// Set the number of audio channels.
`-ac`

// Set the frame size (for raw image)
`-video_size size`

// null device
`/dev/zero`

// audio codec input/output
`-acodec
-codec:a 
-c:a`

// video codec output
`-vcodec
-codec:v
-c:v`

// output format; flv - rtpm, rtpme, rtmps, rtmpt, rtmpte
`-f avi
-f flv`

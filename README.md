# faster-whisper-generate-srt-subtitles
Generate subtitles srt file from an audio/video file. It uses the faster-whisper library, which is much faster than the OpenAI original one
It can also translate it to english. The model "large-v2" has the best quality, while "medium" is a good compromise between quality and speed.

Read more about faster-whisper: https://github.com/guillaumekln/faster-whisper

```


usage: generate-srt.py [-h] input_file
Transcribe audio from a video file and generate an SRT file.
positional arguments:
  input_file  Path to the video file for transcription
options:
  -h, --help  show this help message and exit


How to install faster-whisper:
pip install faster-whisper
```

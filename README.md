# Tool to create rotating image video

Dependencies (for macOS):
```
brew install ffmpeg
pip install --user pillow
```

Create rotating circle video from png with alpha layer and mp3:
```
./img-to-video image.png audio.mp3 out.mp4
```

Create rotating circle video on background from png with alpha layer and mp3:
```
./img-and-bg-to-video bg.png image.png audio.mp3 out-bg.mp4
```

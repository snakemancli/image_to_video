# SnakemanCLI - Image to Video with Audio

This module converts a folder of images into a video file with optional background audio. The video will include transitions and fade effects. Only tested on Arch and Gentoo.

## License

This project is licensed under the Zero-Clause BSD license. See the [LICENSE](LICENSE) file for more details.

## Requirements

- Python 3.x
- ffmpeg
- ffmpeg-python

You can install the necessary Python package with:
```bash
pip install ffmpeg-python
```
```
python image_to_video.py --images path/to/images --output path/to/output [--audio path/to/audio]
```


# Unmanic Plugins by BishopDynamics

## Included Plugins

### `video_transcoder_apple`
Transcode the video streams of a video file using Apple videotoolbox hardware accelleration on Apple Silicon SoCs

Install this instead of the official `video_transcoder` plugin, to take advantage of hardware acceleration on Apple Silicon.

This is pretty much just a search-and-replace of `libx265` -> `hevc_videotoolbox`, and `libx264` -> `h264_videotoolbox`. 

You need to install ffmpeg from [Homebrew](https://brew.sh) to use this:
```bash
brew install ffmpeg
```


## Instructions

### Repo URL:

```
https://raw.githubusercontent.com/bishopdynamics/unmanic-plugins-bishopdynamics/repo/repo.json
```


Follow [Unmanic Documentation](http://docs.unmanic.app/docs/plugins/adding_a_custom_plugin_repo/) 
to add this repo to your Unmanic installation.


## Links

[Unmanic Documentation](https://docs.unmanic.app/docs/)

[License and Contribution](#license-and-contribution)


---
## License and Contribution

This projected is licensed under th GPL version 3. 

Copyright (C) 2021 Josh Sunnex - All Rights Reserved

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:
 
The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

This project contains libraries imported from external authors.
Please refer to the source of these libraries for more information on their respective licenses.

See [CONTRIBUTING.md](docs/CONTRIBUTING.md) to learn how to contribute to Unmanic.

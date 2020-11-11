# Valuable-YouTube-Video-Finder

## The project
The purpose of this project is to enable users to find valuable YouTube videos of their interest independent of YouTubes recommendation system.

## Setup

### YouTube-API-Key
You will need to acquire a YouTube v3 API key, which you can do so easily [here](console.developers.google.com/cloud-resource-manager). A helpful video outlining the process can be found [here](https://www.youtube.com/watch?v=-QMg39gK624). After obtaining the API key, enter it as a string into the [config.yaml file](https://github.com/chris-lovejoy/YouTube-video-finder/blob/master/config.yaml).

### Packages
All requirements are contained within [requirements.txt](https://github.com/chris-lovejoy/YouTube-video-finder/blob/master/requirements.txt).

To install them, execute the following from the root directory:
```
pip install -r requirements.txt
```

## Execution
After configuring the config.yaml file, the function can be executed from the comman line using:

```
python3 ./
```

This will call the [__main__.py function](https://github.com/chris-lovejoy/YouTube-video-finder/blob/master/__main__.py) and output will be printed into the console.


## File-Structure
```bash
|   README.md
|   __main__.py
|   config.yaml
|   requirements.txt
|   video_finder.py "The source code for the program"
```
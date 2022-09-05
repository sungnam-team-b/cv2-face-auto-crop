# Face Detection And Auto Crop
[![Language grade: Python](https://img.shields.io/lgtm/grade/python/g/leblancfg/autocrop.svg?logo=lgtm&logoWidth=18)](https://lgtm.com/projects/g/kenxdrgn/Face-Detection-And-Auto-Crop/context:python)  
A python program that detects all human faces in an image and crops them automatically.

## Optional
The best practice for your project is to use a [virtual environment](https://packaging.python.org/guides/installing-using-pip-and-virtual-environments/).

## Download
```
cd && git clone https://github.com/kenxdrgn/Face-Detection-And-Auto-Crop
```

## Installation (with virtualenv)
```
cd Face-Detection-And-Auto-Crop
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

## Installation (without virtualenv)
```
cd Face-Detection-And-Auto-Crop
pip install -r requirements.txt
```

## Usage
```
python auto_crop.py <image_path> ...
```

## Example
```
python auto_crop.py images/peoples.jpg
```
or
```
python auto_crop.py image/peoples.jpg data/group.png human.jpeg
```
Successfully cropped images will be saved in a folder named "result".

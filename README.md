# Dot Counter

This program counts red, yellow, and green dots from inputted `.jpg` and `.png`
files.

## Example Usage

Given this image

![](images/dots.jpg)

One can...

```sh
python dotcounter.py images/dots.jpg
# No. of red      circles detected = 10
# No. of green    circles detected = 39
# No. of yellow   circles detected = 31
```

You can also use `--show` to visualize the dot and color classification

```sh
python dotcounter.py images/dots.jpg --show
```

## Dependencies

To run `dotcounter.py` you will need numpy, scipy opencv-python matplotlib
installed. Pleaes see `requirements.txt` for specific version constratints.

The code works with Python 3.12.4, not other versions have been tested.

## Install

```sh
# install Python 3.12.4
python -m venv dotcounter-env
source dotcoutner-env/bin/activate

python -m pip install -r requirements.txt
```



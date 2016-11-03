*A pretty, non-sluggish git gui (oh, and it's bug-free!)*

# Build instructions

using Python 3.5.2

## Kivy 1.9

### macOS 

Install Kivy requirements

`$ brew install sdl2 sdl2_image sdl2_ttf sdl2_mixer gstreamer`

## virtualenv

Install virtualenv via pip

`$ pip3 install virtualenv`

Activate the virtual environment

`$ source venv/bin/activate`

Install the requirements

`$ pip install -r requirements.txt`

# Dependency instructions

## virtualenv

When installing new packages, do so using virtualenv.

When packages are installed, update `requirements.txt``

`$ pip freeze > requirements.txt`


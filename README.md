Here's dlib 19.18 egg for python 3.7.4 built on win x64 for running OpenCV with Blender 2.8+

See https://www.youtube.com/watch?v=LK4l9Dl1ch4 for first results.


# Install #

Download the zip file. Copy it.

Go into your Blender python `lib/site-packages` location (something like C:\Program Files\blender\2.81\python\lib\site-packages), paste
and unzip it here, resulting in a `dlib-19.18.0-py3.7-win-amd64.egg` folder.

This way you can call dlib from your python scripts in Blender without the need to compile it on your machine (you would need 15GB for Visual Studio and NVidia SDK installs).



Hope it helps!

This repo will be obsolete once dlib wheel will be available for python 3.7.X

Try `python -m pip install dlib --user` before downloading this one.

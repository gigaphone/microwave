```pip install virtualenv```
```pip install --upgrade  virtualenv```

create virtual environment directory (useful option to exclude global packages --no-site-packages, default option after 1.7)
```virtualenv venv``

start using virtual environment
````source venv/bin/activate``

create a file with all requirements for automated pip install
````pip freeze > requirements.txt``

to list requirements
````pip list``

to install saved r`quirements
pip install -r requirements.txt

done using venv
deactivate

to remove venv for good
rm -rf venv


installed packages
pip install numpy
pip install scipy
pip install matplotlib
pip install pydub


matplotlib makes issues so I did this
echo "backend: TkAgg" > ~/.matplotlib/matplotlibrc
The solution has been described here:
http://stackoverflow.com/questions/21784641/installation-issue-with-matplotlib-python


to play audio from terminal
afplay test.wav

for mac
brew install ffmpeg --with-libvorbis --with-ffplay --with-theora

for linux
apt-get install ffmpeg libavcodec-extra-53

win
download binaries [link](http://builds.libav.org/windows/)



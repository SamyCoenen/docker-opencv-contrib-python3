# docker-opencv-contrib-python3
Dockerfile for OpenCV, OpenCV contrib and Python 3.5.
Including Tesseract-OCR and leptonica.

For use with pycharm this also has ssh access for remote use.
Only one app should be run within one container but the ssh access via docker -it bash doesn't contain sftp.

**In Progress**
You still need to do the following:
make normal non-sudo user
start ssh service manually
depending on your setup, change host port to something else than 22

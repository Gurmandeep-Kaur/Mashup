# Mashup

This repository implements an audio mashup generator using Python. The project consists of a command-line program and a web-based application that automatically downloads YouTube songs of a given singer, trims each audio clip to a fixed duration, and merges them into a single mashup audio file.

---

## Overview

This project demonstrates how multimedia data can be processed programmatically using Python. Given a singer name, number of videos, and audio duration, the system downloads multiple YouTube videos, extracts their audio, trims the first N seconds from each clip, and combines them into one final MP3 file.

Two interfaces are provided: a command-line program and a web service. Both perform the same mashup operation but offer different ways for the user to interact with the system.

---

## Tools and Libraries

The following tools and Python libraries are used:
- yt-dlp for downloading YouTube videos
- MoviePy for audio extraction and merging
- Flask for building the web application

---

## Author

Gurmandeep Kaur

---

# About
A repository where I will store the tools I use for day to day management and automation of tasks related to Philomena-based imageboorus.

## artist-links
At the moment my single most used tool. Used to automate basic information gathering when deciding whether to grant a given artist tag to an individual.

This script outputs all the image IDs found under a given artist tag, along with their upload date, uploader and source

### Requirements
Python 3 and libraries in the requirements.txt, as well as an **API key** of the target Philomena instance, and a filter ID of a filter that won't hide any posts. 

### Installation
pip install -r requirements.txt

### Usage
info.py "artist:tag"

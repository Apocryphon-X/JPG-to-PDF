# JPG-to-PDF CLI Tool

JPG to PDF is a simple Python CLI Tool which merges all the images in a directory as one single PDF. 

> **Note**: Why did I fork this at the time? Well, I simply wanted a CLI tool capable of easily merging the pages of the comics I occasionally download from the internet (like the `Back to the Future` series for example). For some reason the pages came in separate `.jpg` files, so I decided to merge them into a single pdf for easy reading.  
PS: I know there are online tools that already do this, but where is the fun in using them when I can do my own tool?  

```shell
Usage: main.py [OPTIONS] DIRPATH NAME

  Merges all `.jpg` files contained within DIRPATH into a single PDF called NAME.

Options:
  --help  Show this message and exit.
```

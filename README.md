# Compress Image
While working on application performance tuning for some part time work I needed to find a way to compress 100,000+ images.
I wrote a pythons script (attached below) to compress the files for this specific task.
Here’s my version of the image compression script built for compressing images in a given directory to a managebale size using Pil (or Pillow) a python library that does most of the work here.

## Installation

##### Dependencies
Install PIL or Pillow
```
    pip install Pillow
```

## Usage
1. Download above python script. 

2. Create directory named "input" in same directory where above python code it present.

3. Put All your images that has to be compressed inside "input" directory 

4. All compressed images will be stored in directory named "output"

5. Select quality level for output images

```
		foo.save(out_path, optimize=True, quality=<your desired quality level>)
```

3. Run script
```
		python image_compress.py
```



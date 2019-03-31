# FlipImages
Simple script to flip images of a specified path.

### How to use?
Run ```FlipImages.py```, and specify the path of the images you want flipped as a command-line argument.

### Example
```python FlipImages.py C:\Users\Alan\Desktop\FolderOfImages```

### Running on macOS/Linux
- To run on macOS or Linux you'll have the change 2 lines of code (lines 7 and 9).

#### Lines to change

- Change line 7 to ```originalImage = Image.open(pathOfPictures + "/" + filename)```

- Change line 9 to ```saveFlippedImage = flippedImage.save(pathOfPictures + "/" + oldName[0] + "_f" + oldName[1])```

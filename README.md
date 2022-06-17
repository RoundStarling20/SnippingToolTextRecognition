# SnippingToolTextRecognition
A snipping tool that copies text in the image to the clipboard

Original snipping-tool application made by [harupy](https://github.com/harupy/snipping-tool)

I saw the need to be able to copy text like code or windows errors from their respective non copyable window and be able to past them wherever I wanted.

### Opencv issue
I noticed after installing requirements that running
```
pip install opencv-contrib-python
``` 
would fix random opencv errors. I don't fully understand this, I did however notice that the opencv errors would start after easyocr was installed.
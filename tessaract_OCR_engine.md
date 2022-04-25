# tessaract_OCR_engine
INTRODUCTION TO OCR:-

-> optical character recognition(converting image text into raw text)
-> The computer doesn't know how to read text from an image so we have to convert the image into some sort of numerical arrays that can be parsed by the ocr system to then convert that image into raw text.
-> tesseract(from google - open source library) to perform ocr.

WORKFLOW:-

PIL(PILLOW)  -> OPEN AN IMAGE, PASSING AN IMAGE,SAVING AN IMAGE.,CROPPING IMAGE.
images-> numerical array that represent pixels. So the pillow loads images into memory as numbers to work with them.

OPENCV  ->  CHANGE AN IMAGE. (opencv allows us to manipulate the image,change according to your needs, can binarize the image(converting it into black and white,grayscale, ocr from tesseract will perform a more efficient model in case of black and white image because it working with less data.)

TESSERACT(PYTESSERACT)  ->OCR AN IMAGE



How to Preprocess Images for Text OCR in Python:-
 
 
Binarization:

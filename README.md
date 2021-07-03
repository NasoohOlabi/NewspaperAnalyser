# Newspaper Analyser #
1. the script takes a .zip file containing images and decompress them in a new file with the same name
2. then it processes one image at a time
3. each image then processed through a face detection filter 
4. then the results of process would be stored in a json file
5. then the images in the newspaper get blacked to ease the columns divider
6. the columns divider draws a line dividing columns for the text blocks filter
7. the results too would be stored the json file
8. then the text blocks would be sent to the image-to-text processor
9. then the text would be extracted from the images and also stored in the json file
10. the final results would be outputed on the notepad
11. note: the json file will always be check before any computation extensive process as a form of dynamic programing

# Requirements #
1. zipfile
2. PIL
3. pytesseract
4. cv2
5. numpy
6. kraken


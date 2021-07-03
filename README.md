# Newspaper Analyser #
1. The script takes a .zip file containing images and decompress them in a new file with the same name
2. Then it processes one image at a time
3. Each image then processed through a face detection filter 
4. Then the results of process would be stored in a json file
5. Then the images in the newspaper get blacked to ease the columns divider
6. The columns divider draws a line dividing columns for the text blocks filter
7. The results too would be stored the json file
8. Then the text blocks would be sent to the image-to-text processor
9. Then the text would be extracted from the images and also stored in the json file
10. The final results would be outputed on the notepad
11. Note: the json file will always be check before any computation extensive process as a form of dynamic programing

# Requirements #
1. zipfile
2. PIL
3. pytesseract
4. cv2
5. numpy
6. kraken


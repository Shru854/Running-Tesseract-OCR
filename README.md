Running-Tesseract-OCR

Step 1:  1st download  or scan an image with high resolution.
Step 2: open terminal where your scan or download image is present. 
Step 3: Now  type command to copy it into main tesseract ocr folder 
	$ sudo cp -r image name /usr/share/tesseract-ocr/4.00/name_of_folder_where_image _will_store
Step 4: open terminal in /usr/share/tesseract-ocr/4.00
Step 5: type command 
 	$ sudo tesseract input_folder_name//"image _name.jpg,png output_folder_name//name_of_editable_file -l write_lang_code_provide_in_tessdata-master(ex:hin,eng,)
Step 6: Make sure you have devnagri traineddata avialble and present in tessdata folder which is located at 4.00 folde.All language traineddata should present in tessdata foolder.

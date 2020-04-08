# Running-Tesseract-OCR
# 1st download  or scan an image with high resolution 
# open terminal where your scan or download image is present 
# Now  type command to copy it intomain tesseract ocr folder 
$ sudo cp -r image name /usr/share/tesseract-ocr/4.00/name_of_folder_where_image _will_store
# open terminal in /usr/share/tesseract-ocr/4.00
# type command 
 $ sudo tesseract input_folder_name//"image _name.jpg,png output_folder_name//name_of_editable_file -l write_lang_code_provide_in_tessdata-master(ex:hin,eng,)
 # make sure you have devnagri traineddata avialble and present in tessdata folder which is located at 4.00 folde.All language traineddata should present in tessdata foolder.

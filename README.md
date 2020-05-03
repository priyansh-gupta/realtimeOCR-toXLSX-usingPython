# realtimeOCR-toXLSX-usingPython
we provide with a dataset of RCs then the model prepares an excel  showing what was the text output for each image. 

APPROACH->
	Market have various paid API for OCR which can easily perform the given task .
	but we can not customize those API according to our need .
	thus instead of using Amazon TEXTRACT(easy to use) i used TESSERACT API(requires fundamental knowledge)
	it is always good to be a creator rather than using taylormade APIs

GOAL-> 
	using tesseract i can showcase my coding skills in python and can make custom made model
	my model is not accurate but is made keeping the coding basics in mind.

Challenges->
	the given dataset was very difficult to work with . All the images had different format and layout.
	images were bulr , were not properly cropped , had imporper lighting ,etc
	it was very difficult to classify the information as it doesnot follow any fixed format.
	
solutions->
	TESSERACT is a very powerfull free API, it can easily extract text from any image .
	I converted the output of OCT into upper case  to solve the problem of  Name and NAME.
	I used core basic python programming to solve the given dataset.

FUTURE SCOPE->
	I plan to use Deep learning and machine learning to create a smart model which can detect text very easily 
	and treat with the problem of non-simillar format.
	we can use CNN & RCNN with YOLO to have a better output at real time. 
  
	

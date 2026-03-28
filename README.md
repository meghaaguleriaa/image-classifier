Project title : AI Image classifier 

Working:
The application observe and read the image uploaded to it and classifies it and tells about the image.
The AI classifier gives the top 3 traits/features of the uploaded image. 
Thus the image is classified into 3 defined categories.
It uses the pre trained model MobileNetV2- Tensorflow 

To Install:
1. uv
2. streamlit
3. tensorflow
4. opencv
example: Write "pip install uv" in your pc terminal/ command prompt


The project uses
1. uv for fast and efficient dependency management , instead of pip.
2. streamlit for the interactive web interface allowing user to upload image and view classification results in real time.
3. tensorflow , for its predifined model- MobileNetV2 , to recognize image
4. opencv to resize the image to the required size of the AI model

How to use :
1. Clone the repository 
2. Install the required technologies - uv, streamlit , opencv, tensorflow
3. On project terminal write
"uv init" -- to initalise uv
"uv add streamlit tensorflow opencv-python numpy pillow" -- for streamlit and MobileNetV2
"uv run streamlit run app.py" for running project

5. It will give the link for local host
6. click the link, application may take 2 minutes to fully load in the browser.
7. After the application loads, click on upload image and uploaded the image to be classified
8. Then click on "Analyze image"
9. It will load and provide the classifications of the image
10. This application recognize the object in the image and categorize it and provide the best
   three specification predicted by the AI model.



Contact details :
     Name: Megha Guleria
     Registration number: 25BCE10168
     Mail: megha.25bce10168@vitbhopal.ac.in
      
     
Notes:
 1. The project requires internet only during the first run to download the pretrained model. After that, it can run offline.
 2. Screenshot and the video of the working application are included in  the screensots and recording folder respectively.

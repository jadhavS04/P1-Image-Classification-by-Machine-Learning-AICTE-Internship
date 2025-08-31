# P1-Image-Classification-by-Machine-Learning-AICTE-Internship 

 I have done this project to classify images by using CNN Model and pre Trained MobileNet Model. I created the streamlit app for the same.  

 ## How to run the code   
 
  1. Download repository:
https://github.com/jadhavS04/P1-Image-Classification-by-Machine-Learning-AICTE-Internship

 2. Download anaconda:
https://www.anaconda.com/download

 3. Create and activate a virtual environment:
open the anaconda prompt-> conda create --name aicte_ImgClass python=3.9
to activate environment-> conda activate aicte_ImgClass
to list enviroment-> conda env list

 4. Install the required packages:
tensorflow-> conda install -c conda-forge cudatoolkit=11.2 cudnn=8.1.0
Anything above 2.10 is not supported on the GPU on Windows Native->
python -m pip install "tensorflow<2.11"
Verify the installation->
python -c "import tensorflow as tf; print(tf.config.list_physical_devices('GPU'))" 
numpy-> pip install numpy    
matplotlib-> pip install matplotlib   

 5. Create Folder
move all repository files to folder AICTE Internship ImgClass pro:
eg. open folder path-> (aicte_ImgClas) C:\Users\subha\.anaconda\AICTE Internship-ImgClass pro

 6. Start the Streamlit app:
(aicte_ImgClas) C:\Users\subha\.anaconda\AICTE Internship-ImgClass pro> streamlit run newApp.py 

 7. Open the app: The app will open in your default web browser. If not, navigate to http://localhost:8501 

Contributing
Feel free to fork the repository, open issues, or submit pull requests to contribute to the project.


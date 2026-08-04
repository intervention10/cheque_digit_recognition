# cheque_digit_recognition
This is a streamlit system which takes in an image and predict the handwritten image of a digit accurately.

how to use it:

create a folder in any of the preferable drive, put files app.py, digit_recognition_model.keras, requirements.txt in it

go to cmd, get to the directory, then type commands like


py -3.11 -m venv myvenv             -- to create a virtual environment
myvenv\scripts\activate.bat         -- to activate the scripts
pip install -r requirements.txt     -- to install the requirements written in requirement.txt. (streamlit,numpy,tensorflow,pillow etc)
streamlit run app.py                -- to run the web-based app

after its properly run, the system will open in browser, where itll ask you to upload an image, then you have to upload the handwritten image sample_digit_5.png
and after the upload, the system will predict the image accurately as 5, as shown in the output.jpg

ive uploaded the ipynb file too, which you can run in anacondas->jupiter notebook , where you can alter and save everything as per your needs.

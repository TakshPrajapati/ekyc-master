
<p align="center">
  <img src="https://github.com/varunmamtora06/ekyc/blob/master/assets/DisplayImage.PNG" width="720px" height="360px" alt="ekyc" title="EKYC"/>
</p>


### Problem Statement (PS) 

- Earlier KYC verification was done in person,but due to COVID-19, this can't be done
- Banks are trying a way to implement a way to perform KYC virtually, since KYC procedures defined by banks are to ensure their customers are real, and to assess, and monitor risks.
- The user needs to upload the necessary  government documents, eg: Aadhar card, PAN card, voter-id, electricity-bill.
- After uploading the documents the person needs to submit a 10 sec video to determine that the person uploading these documents is a legit user.
- The web application incorporates machine learning for recognizing and matching the faces of user with the documents uploaded.



<!-- about us & view patient -->
### Tech Stack
- Frontend
	- HTML5
	- CSS3
	- JavaScript
    - Bootstrap4
- Backend
    - Django framework
- Database
    - SQLite
- Machine Learning
    - face-recognition
    - opencv-python 
    - NumPy
    - CMake
    - Dlib

### Local Setup
- Install CMake, Dlib and face-recognition libraries
- Clone repository.
- Setup virtual environment
- Exceute `pip install -r requirements.txt`.
- run `python manage.py runserver`.
- Go to `127.0.0.1::8000` in your web browser.



`
### Problem Statement (PS) 

- Currently, Know Your Customer (KYC) is largely an offline and manual process OR non-interactive online process.  
- Create an online interactive process to do video KYC which is intuitive and self-sufficient. KYC should capture the user’s live photograph
- and their basic details like name, DOB, address, PAN card / Aadhaar, signature, income range, and type of employment in a conversational manner.
- This tool should be highly inclusive and should have high reach across languages and generations irrespective of financial and education gap.

### 2-Step Authentification 
Step1: Video transcript authentification by reading the Generated Code on the Screen and creating the video by reading it.
Step2: After filtering verified users from Step1, the backend team looks into the video manually to ensure the verified users.

### Demo Link

 - https://drive.google.com/file/d/1tY9AbCOFxBJVhypXV9lVotZn1Bu6gG7k/view?usp=sharing
 - Applied 2FA step to verify KYC using RPA


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
- Go to `127.0.0.1::8000` in your web browser.`

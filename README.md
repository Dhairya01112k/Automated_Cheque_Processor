# ChecQPro - Automated Cheque Processing and Fraud Detection

<b>INTRODUCTION</b>: Through this project, we are aiming to automate the process of cheque processing. In order to perform the task of cheque verification, we developed a tool which acquires the cheque leaflet key components, essential for the task of cheque clearance using image processing and deep learning methods. These components include the bank branch code, cheque number, legal as well as courtesy amount, cheque date, account number, and signature patterns.

# Screenshots:

#### Key Parameters of a Cheque
##### Account Number
![68747470733a2f2f73746f726167652e676f6f676c65617069732e636f6d2f6368657175655f696e666f2f3136363336373231353233353263715f6163636f756e745f6e756d2e6a7067](https://user-images.githubusercontent.com/55848343/205454378-a9a4e183-0fb5-4c80-a92a-21544f0d6e3e.jpg)
##### Legal Amount
![68747470733a2f2f73746f726167652e676f6f676c65617069732e636f6d2f6368657175655f696e666f2f3136363336373231353233353263715f616d6f756e745f696e5f776f7264732e6a7067](https://user-images.githubusercontent.com/55848343/205454438-06982d7b-bd44-4d8d-9851-589bb7acba50.jpg)
##### Courtesy Amount
![68747470733a2f2f73746f726167652e676f6f676c65617069732e636f6d2f6368657175655f696e666f2f3136363336373231353233353263715f6669677572652e6a7067](https://user-images.githubusercontent.com/55848343/205454465-64785ec9-b494-4ac0-94cb-b034456214d8.jpg)
##### Cheque Number
![68747470733a2f2f73746f726167652e676f6f676c65617069732e636f6d2f6368657175655f696e666f2f3136363336373231353233353263715f6368657175655f6e756d2e6a7067](https://user-images.githubusercontent.com/55848343/205454492-2cb4cfc6-6178-4c44-bb80-dd4f5df40dfd.jpg)
##### Cheque Date
![68747470733a2f2f73746f726167652e676f6f676c65617069732e636f6d2f6368657175655f696e666f2f3136363336373231353233353263715f646174652e6a7067](https://user-images.githubusercontent.com/55848343/205454508-d317433e-dc3b-4eee-9e7a-669a5b147ffb.jpg)
### User Interface:
![191278193-06a6d682-92b5-4ae4-a5a2-3fe3763fce29](https://user-images.githubusercontent.com/55848343/205454728-840748b8-307e-450c-9710-b0ef0041416c.png)
![191279204-5c03868d-1e9c-4b3c-aacc-fe57351a3188](https://user-images.githubusercontent.com/55848343/205454732-76180664-44ef-4afb-b477-f5de834245a3.png)
![191278176-58112a28-d607-4df3-8b4c-00976190ede3](https://user-images.githubusercontent.com/55848343/205454734-8cd7255e-b123-425a-9a51-001e39507fd1.png)
![191278183-bdcb68ec-95c9-46bc-aba9-94c1d4740e31](https://user-images.githubusercontent.com/55848343/205454738-7809bffe-f9bc-4656-a5fa-ff46f716408f.png)
![191279304-d73410b7-f218-47b6-9cad-7e5830d4ff28](https://user-images.githubusercontent.com/55848343/205454775-8d51ce34-a971-4ddf-8966-92865287a181.png)
![191278208-9daf47b9-1ad7-46c0-91cc-5a92c8132d62](https://user-images.githubusercontent.com/55848343/205454745-db251b28-1729-4002-b5d2-755ac2b8b6d1.png)

# Instructions:
### Prerequisites:
1. Python3 should be installed on the system.
2. Need an active internet connection.
### To run the project loclly, follow the following steps:

1. Setup a virtual environment:
    For ubuntu:
        1. sudo apt install virtualenv
        2. virtualenv -p python3 name_of_environment
        3. To activate: source name_of_environment/bin/activate
    For windows:
        1.	pip install virtualenv
        2.	python -m venv <path for creating virtualenv>
        3.	To activate: <virtualenv path>\Scripts\activate

2. Clone the repository
3. Change the directory: cd AutomatedChequeProcessing
4. Install the requirements: pip install -r requirements.txt
5. Create service account on Google Cloud Platform and enable Vision API service.
6. Create private key for the service account in JSON format.
7. Rename JSON file to chequeprocessing.json and place the file in the root of the project.
8. Follow official documentation to install Google Cloud SDK (refer https://cloud.google.com/sdk/docs/install-sdk).
9. Run the server: python3 app.py

# ChecQPro Express Application:
This Flask app uses the ChecQPro Application as the Frontend, Backend and Database of the project.

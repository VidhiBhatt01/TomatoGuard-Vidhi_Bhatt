# Setup Instructions:

1. Fork and Clone this repo.
2. Install Python on your device. ([Setup instructions](https://wiki.python.org/moin/BeginnersGuide))

## Training and building the model 
3. Open Anaconda and run the Model Code.ipynb file present in the Code folder.

## Setting up the Backend
4. Open command prompt.
5. Navigate to the api folder of this project.
6. Create a virtual env 
```console
$ python3 -m venv test
```
7. Activate the virtual env
```console
venv\Scripts\activate
```
8. Install the required packages
```console
pip install -r requirements.txt
```
9. Run the main.py using the command
```
python main.py
```
10. Use postman to send a request to the server

## Setting up the frontend
11. Install Nodejs ([Setup instructions](https://nodejs.org/en/download/package-manager/))
12. Install NPM ([Setup instructions](https://www.npmjs.com/get-npm))
13. After installation, open the powershell
14. Navigate to the frontend folder
15. Install dependencies
```bash
cd frontend
npm install --from-lock-json
npm audit fix
```
16. Run the frontend
```
npm run start
```
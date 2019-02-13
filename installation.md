## Linux Installation Manual
1. **Download PEARLS** : Download the zip package or clone directory contaning PEARLS package and extract the package.

2. **Create Virtual Environment** : You need to have installed virtualenv, if not installed install using ``` pip install virtualenv ``` before running next commands. Run command ```virtualenv djangoenv```. It will create folder named django containing python distribution.

3. **Activate Virtual Environment** : For running application you need to activate virtual ennvironment.
```sh
$ source ./djangoenv/bin/activate
```
4. **Setup Environment** : Run following command after activation  
```sh
$ pip install -r requirements.txt
```
5. **Run Server** : Next run server by command:
```sh
$ python manage.py runserver
```
6. Open index.html file from Frontend folder in your PEARLS repo in browser and you are ready to go. :)

## Windows Installation Manual
1. Install python 2.7.15
    1. Download exe file from download page
        - [Python page link](https://www.python.org/downloads/release/python-2715/)
        - [PEARLS Drive Link]()
    2. Run installer and at the below page add **pip and python to path**
    ![Installation Image](./image/PythonInstaller.png)
2. Next install virtualenv by running the given command
```sh
$ pip install virtualenv
```
3. Create virtual ennvironment by
```sh
$ cd C:\User\User\Documents
$ virtualenv pearls-env  
```
4. Next you have to activate your virtual ennvironment by
```sh
$ .\pearls-env\Scripts\activate
```
5. Next move to the your PEARLS repo
```sh
$ pip install -r requirments.txt
```
6. navigate to Backend/backend_server and run following and run django server
```sh
$ cd .\Backend\backend_server\
$ python manage.py runserver
```
7. Open index.html file from Frontend folder in your PEARLS repo in browser and you are ready to go. :)

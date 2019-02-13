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

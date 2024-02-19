# Todo-app
## Containerized Python-Django application And deployed it using docker
# Step 1 
1] Clone The repository into your local terminal 
```bash
$ git clone https://github.com/shreys7/django-todo.git
```
2] Cloned the repository into My Vscode integrated terminal

![Screenshot 2024-02-19 004458](https://github.com/AdityaAgasti007/Todo-app/assets/159541012/cab6f5c6-d6c1-4e0f-865e-3b04e829b1fc)

3] Installed the Virtual enviroment into your local terminal 
``` bash
$ pip install virtualenv
```
4] Setup the virtual enviroment 
```bash
$ virtualenv -p python3.10 env
```
5] This command will execute the Activate script within the Scripts directory of your virtual environment, setting up the environment variables and modifying the shell prompt to indicate the activated environment.
```bash
$ .\env\Scripts\Activate
```
6]  Install the django application into your local terminal 
```bash
$ pip install django 
```
7] Update the pip 
```bash
$  python.exe -m pip install --upgrade pip
```
8] This will create all the migrations file (database migrations) required to run this App
```bash
$ python manage.py makemigration
```
9] Now, Apply the migration run following command
```bash
 $ python manage.py migrate
```
10] One last step and then our todo App will be live. We need to create an admin user to run this App. On the terminal, type the following command and provide username, password and email for the admin user
```bash
$ python manage.py createsuperuser
```
11] That was pretty simple, right? Now let's make the App live. We just need to start the server now and then we can start using our simple todo App. Start the server by following command
```bash
$ python manage.py runserver
```
12] Once the server is hosted, head over to http://127.0.0.1:8000/todos for the App.

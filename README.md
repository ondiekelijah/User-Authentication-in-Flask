# User-Authentication-in-Flask

## Set up & Installation.

### 1 .Clone/Fork the git repo and create an environment 
                    
**Windows**
          
```bash
git clone https://github.com/Dev-Elie/User-Authentication-in-Flask.git
cd User-Authentication-in-Flask
py -3 -m venv venv

```
          
**macOS/Linux**
          
```bash
git clone https://github.com/Dev-Elie/User-Authentication-in-Flask.git
cd User-Authentication-in-Flask
python3 -m venv venv

```

### 2 .Activate the environment
          
**Windows** 

```venv\Scripts\activate```
          
**macOS/Linux**

```. venv/bin/activate```
or
```source venv/bin/activate```

### 3 .Install the requirements

Applies for windows/macOS/Linux

```
pip install -r requirements.txt
```
### 4 .Migrate/Create a database

```python manage.py```

### 5. Run the application 

**For linux and macOS**
Make the run file executable by running the code

```chmod 777 run```

Then start the application by executing the run file

```./run```

**On windows**
```
set FLASK_APP=routes
flask run
```

Login           |  Register
:-------------------------:|:-------------------------:
![Sample](https://github.com/Dev-Elie/User-Authentication-in-Flask/blob/main/static/login.png)  |  ![Sample](https://github.com/Dev-Elie/User-Authentication-in-Flask/blob/main/static/register.png)

</br>
<div align="center"><h1>Follow me on Twitter</h1></div>
<p align="center"> <a href="https://twitter.com/dev_elie" target="blank"><img src="https://img.shields.io/twitter/follow/dev_elie?logo=twitter&style=for-the-badge" alt="dev_elie" /></a> </p>




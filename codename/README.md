#### Setup Virtual Env


```
mkvirtualenv codename
cd codename
pip install -r requiements.txt
```

#### Run django application locally
```
cd codename

# ensure your docker daemon is running
docker run -p 6379:6379 -d redis:5

python manage.py runserver
```
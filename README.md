# octopus
Telegram-bot for tracking health indicators (Django+PostgreSQL) and getting analysis based on this data.


# How to run



``` bash
git clone https://github.com/annachul/octopus
cd octopus
```

Create virtual environment (optional)
``` bash
python3 -m venv dtb_venv
source dtb_venv/bin/activate
```

Install all requirements:
```
pip install -r requirements.txt
```


Run migrations to setup PostgreSQL database:
``` bash
python manage.py migrate
```

Create superuser to get access to admin panel:
``` bash
python manage.py createsuperuser
```

Run bot in pooling mode:
``` bash
python run_pooling.py 
```




# nippontrade.club

mkdir nippontrade_core
cd nippontrade_core
       place requirements.txt here
       run pip install -r requirements.txt
django-admin startproject nippon_trade
       this creates files(nippon_trade, manage.py)
cd nippon_trade
       includes __init__.py, settings.py, urls.py, wsgi.py
vi settings.py
       change DATABASE info

DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.mysql',
        'NAME': 'nippon_trade',
        'USER': 'nippontrade',
        'PASSWORD': '**************',
        'HOST': 'localhost',
        'PORT': '3306',
    }
}

[7:42] 
LANGUAGE_CODE = 'ja'
TIME_ZONE = 'Asia/Tokyo'




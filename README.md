1. Install dajngoframework ==>pip install djangorestframework
2. Add 'rest_framework' to your INSTALLED_APPS setting.==>INSTALLED_APPS =  'rest_framework',
3. Install  djangorestframework-simplejwt =>pip install djangorestframework-simplejwt



 4. In settings.py, add rest_framework_simplejwt.authentication.JWTAuthentication to the list of authentication classes:
    REST_FRAMEWORK = {
        'DEFAULT_AUTHENTICATION_CLASSES': (
            
            'rest_framework_simplejwt.authentication.JWTAuthentication',
        ) 
    }

5. add rest_framework_simplejwt to INSTALLED_APPS.==>'rest_framework_simplejwt',

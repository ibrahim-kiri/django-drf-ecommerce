# generate random secret key
from django.core.management.utils import get_random_secret_key
print(get_random_secret_key())

# Commands
python manage.py spectacular --file schema.yml
# Django-Stripe-Payment-Intent


First create a table

python manage.py makemigrations products python manage.py migrate products

Then create superuser go to http://127.0.0.1:8000/admin , there you can see product table . Add a product for testing purposes . Make payment then you can see your payment intent in Stripe Dashboard.

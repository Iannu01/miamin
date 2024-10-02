# E-Commerce Website (Django)

## Overview
This project is a fully functioning e-commerce website built using Django, providing features such as product listings, filtering, cart management, user authentication, and online payments. The website allows users to browse products, add them to their cart, and complete the purchase via a secure payment gateway.

## Features
- **User Authentication:**
  - Sign up, login, and logout functionality using `django-allauth`.
  - New users can create an account and login to access the shopping experience.
  
- **Product Management:**
  - Users can browse a catalog of products, view details, and filter products based on categories or attributes.
  
- **Shopping Cart:**
  - Users can add items to their cart and modify quantities before proceeding to checkout.
  
- **Order and Payment:**
  - Users can place an order and make payments via Stripe integration.
  
- **Crispy Forms Integration:**
  - For beautiful and responsive forms using `django-crispy-forms`.

## Technologies
- **Framework:** Django 2.2.14
- **Frontend:** HTML, CSS, Django Template Engine
- **Payments:** Stripe API integration
- **User Authentication:** Django Allauth
- **Miscellaneous:** 
  - Debugging tools (`django-debug-toolbar`)
  - Form management (`django-crispy-forms`)
  - Static file handling (Pillow for image processing)

## Known Issues
- **Post-Signup Exception:**
  - After successfully signing up, the user encounters an exception page.
  - The account is created, but the user must manually go back to login using the same credentials.

## Requirements

autopep8==1.4.4
certifi==2019.3.9
chardet==3.0.4
charset-normalizer==3.3.2
defusedxml==0.6.0
Django==2.2.14
django-allauth==0.39.1
django-countries==5.3.3
django-crispy-forms==1.7.2
django-debug-toolbar==1.10.1
idna==2.8
oauthlib==3.0.1
pep8==1.7.1
pillow==10.4.0
pycodestyle==2.5.0
python-decouple==3.1
python3-openid==3.1.0
pytz==2018.5
requests==2.21.0
requests-oauthlib==1.2.0
sqlparse==0.2.4
stripe==2.27.0
urllib3==1.24.2


## Setup Instructions
1. Clone the repository.

git clone https://github.com/Iannu01/miamin.git


2. Navigate to the project directory.
cd miamin

3. Install dependencies.
pip install -r requirements.txt

4. Apply migrations.
python manage.py migrate

5. Run the server.
python manage.py runserver

6. Access the site at `http://127.0.0.1:8000`.

## Contributions
Contributions are welcome! Feel free to open a pull request or raise issues.

## License
This project is licensed under the MIT License.

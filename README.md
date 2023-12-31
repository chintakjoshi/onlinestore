# Django E-commerce

This is a very simple e-commerce website built with Django.

## Project Summary

The website displays products. Users can add and remove products to/from their cart while also specifying the quantity of each item. They can then enter their address and choose Stripe to handle the payment processing.

![alt text](https://justdjango.s3-us-west-2.amazonaws.com/media/thumbnails/djecommerce.png "Logo")

---

## Running this project

To get this project up and running you should start by having Python installed on your computer. It's advised you create a virtual environment to store your projects dependencies separately. You can install virtualenv with

```
To execute this project on your local machine, it is necessary to have Python version 3.8 installed.
```

```
pip3 install virtualenv
```

Clone or download this repository and open it in your editor of choice. In a terminal (mac/linux) or windows terminal, run the following command in the base directory of this project

```
python3 -m venv venv
```

That will create a new folder `env` in your project directory. Next activate it with this command on mac/linux:

```
source env/bin/activate
```

Then install the project dependencies with

```
pip install -r requirements.txt
```

Now you can run the project with this command

```
python manage.py runserver
```

To Stop the server and deactivate the environment

```
Control + C and deactivate
```

**Note** if you want payments to work you will need to enter your own Stripe API keys into the `.env` file in the settings files.

# About Us
This project is carried by a group of graduate students studying at Saint Louis University and a part of SLU Global Grads.

# Team Members
1) Chintak Joshi - Team Lead - MSCS
2) Nikhar Viroja - Developer - MSCS
3) Pruthviraj Butiya - Developer - MSCS
4) Sowmya - Developer - MSIS
5) Prathima Chowdary - Developer - MSCS
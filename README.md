# Instagram

#### Created By Amon Wanyonyi

## Description

Instagram is a simple photo web application to showcase beautiful pictures and designs. Users get to view photos updated by other users. They can also click on a photo and view more details about it. Users can also leave comments or even like based on selected images.

## Setup Requirements

- Django 3.2.7
- Pip
- Python 3.8
- PostgreSQL
- Cloudinary (for image upload)

```
   - CLOUD_NAME
   - API_KEY
   - API_SECRET
```

## Setup Installation

- Copy the github repository url
- Clone to your computer
- Open terminal and navigate to the directory of the project you just cloned to your computer
- Run the following command to start the server using virtual environment

```
python3.8 -m venv --without-pip virtual
```

- To activate the virtual environment

```
source virtual/bin/activate
```

```
curl https://bootstrap.pypa.io/get-pip.py | python
```

```
pip install -r requirements.txt
```

- To copy .env.example to .env

```
cp .env.example .env
```

- Edit the .env file and replace the values with your own Cloudinary credentials and database credentials

- To run the server

```
python manage.py runserver

```

- Open the browser and navigate to http://127.0.0.1:8000/ to see the application in action

## Technologies Used

The following languages have been used on this project:

- HTML
- CSS
- Bootstrap
- Python
- Django
- PostgreSQL

## Support and contact details 

To make a contribution to the code used or any suggestions you can click on the contact link and email me your suggestions.



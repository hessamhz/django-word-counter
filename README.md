# Django Word Counter
Django Word Counter is a web application built with Django that allows users to count the number of words in a text input. It provides a simple and straightforward interface for users to enter their text and get an instant word count.

## Installation
### Docker Installation
This project can be pulled from the docker hub registry. 
1. Pull the Image from docker hub.
``` 
docker pull hessam21/django-word-counter:latest
```
2. Run the image using docker (assign any port, name and etc it is just a sample).
```
docker run -p 8000:8000 hessam21/django-word-counter
```
3. Open your browser and access it via http://localhost:8000!

### Normal Installation
1. Clone the repository
2. Navigate to the requirements directory and install the requirements 
For testing you have to install dev.
```
pip install -r dev.txt
```
For only running the project you can install common.
```
pip install -r common.txt
```
3. Migrate the Django base models.
```
python manage.py migrate 
```
4. Run the server.
```
python manage.py runserver
```
5. Open your browser and access it via http://localhost:8000!

## Usage
1. Enter your text in the provided input field.
2. The word count will be displayed below the input field.


## Extra Features
+ Test coverage: The project includes unit tests to ensure the correctness of the word count functionality and form validation.
+ Docker support: The project includes a Dockerfile for easy deployment and containerization.

## License
The Django Word Counter project is licensed under the MIT License.


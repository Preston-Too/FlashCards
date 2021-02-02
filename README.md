# FlashCards
## Author
[Preston-Too](https://github.com/Preston-Too)

## Live Link
* [here] (https://flash-flashcards.herokuapp.com)

## Description
 FlashCards is a project made to enable users to register and post their notes. Studying made easier by use of FlashCards to aid on memorization of important information.

## User Stories
What the user does...
* A user must be authenticated to see his flashcards.
* A user's flash card can contain a title with some notes.
* Flashcards should be organized according to subjects/courses.
* A user can delete or update a flash card he has created.
* A user should see when the flash card was created and when it was last updated.


## Installation / Setup instruction
One can follow the following steps to get the project .......
#### The application requires the following installations to operate 
* python3.6
* pip

#### Cloning the repository:
```https://github.com/Preston-Too/FlashCards.git```

### Navigate into the folder and install requirements
```cd project-awwards pip install -r requirements.txt ```

### Install and activate Virtual
```- python3 -m venv virtual - source venv/bin/activate ```

### Setup Database
SetUp your database User,Password, Host then make migrate
```python manage.py makemigrations```
```python manage.py migrate ```

### Run the application
```python manage.py runserver ```

### Testing the application
```python manage.py test ```

Open the application on your browser 127.0.0.1:8000.

## Technologies Used

* python3.8
* Django
* Bootstrap
* HTML / CSS


## Known Bugs
* There are no known bugs at the moment

## Contact Information 

If you have any question or contributions, please email me at [toopreston@gmail.com]

## License
* [[License: MIT]](LICENCE.md)
* Copyright (c) 2020 **Preston Too**
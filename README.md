# Python Quiz Game
A simple quiz game built with python

## Table of contents

- [Table of contents](#table-of-contents)
- [Features](#features)
- [Project Structure](#project-structure)
- [Requirments](#requirments)
- [Intsallation](#intsallation)
- [Envoirment Setup](#envoirment-setup)
- [Usage](#usage)
- [Example Output](#example-output)
- [Roadmap](#roadmap)
- [Contributing](#contributing)
- [License](#license)
- [Author](#author)

## Features
- Quiz System
  - Asks the player multiple question
  - Checks the awnsers automatically
  - Calculating the final score
- Results storage
  - save quiz results in `results.txt`
- Admin Mode
  - asks for the admin password
  - checks if the password is correct
  - keeps the private information outside the main python file
  - loads the password from `.env`

## Project Structure

```text
python_quiz_game/
│   main.py
│   question.py
│   requirements.txt
│   .env.example
│   .gitignore
│   README.md
```
### File Description

- `main.py` - main file used to run quiz game
- `question.py` - stores questions and answers
- `requirements.txt` - lists the python packages needed for the project
- `.env.example` - shows the enviroment variables needed by  the project
- `.gitignore` - tells git which files and folders should not be tracked
- `README.md` - contains the project documention

## Requirments
before running the project, make sure you have:
- `python 3`
- `python-dotenv`


## Intsallation
1. open terminal in the project folder.
2. chech that python is installed:
```bash
python --version
```
3. intall the python packages:
```bash
pip install -r requirments
```
## Envoirment Setup
1. create a `.env` file from `.env.example`:
```bash
cp .env.example .env
```
2. open the new `.env` file
3. replace the example value with your own password
```text
QUIZ_ADMIN_PASSWORD=your_password_here
```
4. save the file.
> Don not commit your `.env` file because it may contain private information

## Usage
1. open a terminal in the project folder
2. run the quiz game
```bash
python main.py
```
3. choose `yes` or `no` for admin mode
4. if you choose `yes`, enter the password from your `.env` file
5. enter your name
6. answer the questions
7. see your final score and messege
8. your result is saved in `result.txt`

## Example Output

```text
do you want to open admin mode? yes/no: no
what's your name? mehrsam
welcome

what language are we using? javascript
wrong

what command starts git? git
wrong

what command shows git status? git otuput
wrong

your score is: 0 out of 3
keep practicing mehrsam
```

## Roadmap
- [x] add multiple quiz question
- [x] caculate the final score
- [x] save results
- [x] add admin
- [ ] add more quiz questions
- [ ] add difficulty
- [x] add a timer


## Contributing


## License


## Author
created by [mehrsam bahmanyar](https://github.com/Genius-Progarmmer)

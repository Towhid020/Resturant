# Restaurant Management System
This project is a restaurant management system developed using Python-Django. 

# delete migrations -->
find . -path "*/migrations/*.pyc"  -delete
find . -path "*/migrations/*.py" -not -name "__init__.py" -delete


## Installation
To run this project, you need to have Python installed. Create a virtual environment and install the required dependencies from the `requirements.txt` file.

1. Install Python: [Python Official Website](https://www.python.org/downloads/)
2. Create a virtual environment: `python -m venv myenv`
3. Activate the virtual environment:
   - For Windows: `myenv\Scripts\activate`
   - For macOS/Linux: `source myenv/bin/activate`
4. Install the required dependencies: `pip install -r requirements.txt`

## Usage
To start the restaurant management system, follow these steps:

1. Activate the virtual environment (if not already activated): 
   - For Windows: `myenv\Scripts\activate`
   - For macOS/Linux: `source myenv/bin/activate`
2. Run the Django development server: `python manage.py runserver`
3. Open your web browser and go to: `http://localhost:8000`

## Contributing

If you would like to contribute to this project, you can follow these steps:

1. Fork the repository on GitHub.
2. Clone your forked repository: `git clone [https://github.com/Towhid020/Resturant]`
3. Create a new branch: `git checkout -b my-feature`
4. Make your changes and commit them: `git commit -m "Add new feature"`
5. Push your changes to your forked repository: `git push origin my-feature`
6. Submit a pull request on the original repository.
   
## Contact
If you have any questions or feedback, feel free to reach out to us at [towhidulislam.mail@gmail.com]
facebook:(https://www.facebook.com/Towhid020/).

## License
Copyright (c) Django Software Foundation and individual contributors.
All rights reserved.

## Language Specification
Language: Python
Backend: Django
Frontend: HTML, CSS, BootStrap
Database: SQL

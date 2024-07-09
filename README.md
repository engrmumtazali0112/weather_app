# WeatherWise App

![1](https://github.com/engrmumtazali0112/weather_app/assets/156393630/1137af63-4f49-4717-a98a-45980429a68f)


## Overview
WeatherWise App is a dynamic and responsive web application providing accurate and up-to-date weather reports. Developed using Django, it leverages the OpenWeatherMap API to fetch weather data for multiple cities, displaying current conditions and a 10-day forecast.

## Features
- **User-Friendly Interface**: Designed with Bulma CSS for a sleek and responsive experience.
- **Real-Time Updates**: Get the latest weather information with just a few clicks.
- **Error Handling**: Robust handling of network issues and missing data.
- **Scalable**: Add multiple cities to monitor weather conditions in various locations.

## Demo
![code](https://github.com/engrmumtazali0112/weather_app/assets/156393630/c6592775-eb85-4cb5-8342-feb35e3a6789)
![database](https://github.com/engrmumtazali0112/weather_app/assets/156393630/9c2aa10a-15c5-46de-b826-5ff4a8e19729)



## Installation

1. Clone the repository:
   git clone https://github.com/engrmumtazali0112/weather_app/
   cd WeatherWiseApp
   Create and activate a virtual environment:


python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
Install dependencies:


pip install -r requirements.txt
Set up the database:


python manage.py migrate
Run the development server:

python manage.py runserver
Open your browser and navigate to http://127.0.0.1:8000.

Usage
Enter city names to fetch weather data and display it in the app.
Contributing
Fork the repository.
Create a new branch:

git checkout -b feature_branch
Make your changes and commit them:

git commit -m 'Add some feature'
Push to the branch:

git push origin feature_branch
Create a new Pull Request.
License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgements
OpenWeatherMap API
Bulma CSS Framework
Contact
Feel free to reach out if you have any questions or suggestions!

Email: engrmumtazali01@gmail.com
LinkedIn: https://www.linkedin.com/in/mumtazali12/

5. **LICENSE**:
   - Include a license file. For most open-source projects, the MIT License is a good choice.

```plaintext
MIT License

[Full text of the MIT License]
.gitignore:
Add a .gitignore file to exclude unnecessary files from your repository.

# Python
*.pyc
__pycache__/
venv/

# Django
db.sqlite3
/static/
requirements.txt:
List all the dependencies required to run your project.

Django>=3.0,<4.0
requests

Detailed Documentation:
Ensure your code is well-commented and provide additional documentation if necessary.
By organizing your repository in this way, you make it easier for others to understand, use, and contribute to your project.

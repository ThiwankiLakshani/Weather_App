# Weather_App
# Weather App with Django

## Description

Welcome to the Weather App with Django! This project is designed to guide you through building a weather application using Django, a high-level Python web framework. This tutorial will walk you through the process of creating a weather app that allows users to get real-time weather information for different locations.

### Features

- **Real-Time Weather Data**: Retrieve current weather conditions, including temperature, humidity, wind speed, and more, using an external API.
- **Search Functionality**: Allow users to search for weather forecasts by city name or zip code.
- **Responsive Design**: Implement a responsive user interface to ensure compatibility across various devices.
- **User-Friendly Interface**: Design an intuitive and visually appealing interface for an enhanced user experience.
- **Caching Mechanism**: Implement caching to reduce the number of API calls and improve application performance.

### Technologies Used

- **Django**: A high-level Python web framework for building web applications.
- **Bootstrap**: A popular CSS framework for building responsive and mobile-first websites.
- **OpenWeatherMap API**: To fetch real-time weather data for different locations.
- **SQLite**: A lightweight, serverless database engine used for storing application data.

### Getting Started

Follow these steps to set up the weather app on your local machine:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/weather-app-django.git
   cd weather-app-django
   ```

2. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Set Up OpenWeatherMap API**:
   - Sign up for an account on OpenWeatherMap and obtain an API key.
   - Replace the API key in `weatherapp/settings.py` with your own key.

4. **Run Migrations**:
   ```bash
   python manage.py migrate
   ```

5. **Start the Development Server**:
   ```bash
   python manage.py runserver
   ```

6. **Access the Application**:
   Open your web browser and navigate to `http://127.0.0.1:8000` to access the weather app.

### Folder Structure

- **/weather**: Contains Django app files, including views, templates, and static assets.
  - **/templates/weather**: HTML templates for rendering weather-related pages.
  - **/static/weather**: Static files like CSS, JavaScript, and images.
  - **/views.py**: Django views for handling HTTP requests and rendering templates.
  - **/urls.py**: URL patterns for routing requests to the appropriate views.
- **/weatherapp**: Django project settings and configuration files.
- **/manage.py**: Django command-line utility for administrative tasks.

### Contributing

We welcome contributions! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch for your feature or bug fix:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add a feature"
   ```
4. Push to the branch:
   ```bash
   git push origin feature-name
   ```
5. Create a pull request.

### License

This project is licensed under the MIT License. See the LICENSE file for details.

### Contact

For any inquiries or support, please contact thilakshi.samaraweera2698@gmail.com.



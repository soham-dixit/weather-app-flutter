<h1 align="center">Weather Application</h1>

<p align="center">
<img src="https://user-images.githubusercontent.com/65973895/221436142-7ad8faec-a47d-46f9-9273-88ae809e6e36.png" width="30%"></img>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<img src="https://user-images.githubusercontent.com/65973895/221436168-ffa77b8c-5af1-4050-a2a0-52ff6d2ce651.png" width="30%"></img> 
</p>

A simple weather app created using [Flutter](https://flutter.dev/) and [Dart](https://dart.dev/) and using API from [WeatherAPI](https://www.weatherapi.com)

## 🎯Features
- Searchable location
- Hourly weather information
- 3 days weather information

## 🚀How to Run

1. Create an account at [WeatherAPI](https://www.weatherapi.com).
2. Then get your API key from https://www.weatherapi.com/my/.
3. Clone the repo
   ```sh
   git clone https://github.com/soham-dixit/weather-app-flutter.git
   ```
4. Install all the packages by typing
   ```sh
   flutter pub get
   ```
5. Navigate to **lib/ui/home_page.dart** and paste your API key to the apiKey variable
   ```dart
   String searchWeatherAPI = 'Paste Your API Key Here';
   ```
6. Run the app using flutter run

## 📜License

Distributed under the MIT License. See `LICENSE` for more information.

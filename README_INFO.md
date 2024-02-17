# Daily Weather Report
🌡️ This Bash script retrieves weather information from the OpenWeatherMap API for your city, changes the temperature from Kelvin to Celsius, and updates the contents of the README.md file in the Git repository.

## Features
- Retrieving Weather Information from OpenWeatherMap API, Temperature Conversion and Retrieval of Current Weather Data
- Data Processing and Format and README.md Generation
- JSON Data Generation

## Getting Started
To use Daily Weather Report, you can follow these steps:

### Fork this repository by clicking the "Fork" button on the top right corner of this page. This will create a copy of the repository in your GitHub account.
then visit the [OpenWeather API](https://openweathermap.org/api) website, then register if you don't have an account, after completing the registration then click `My API keys`

![image](https://github.com/Julius-Ulee/Daily-Weather-Report/assets/61336116/98c77a58-c3fc-4fbe-a6ec-6e113ee3e98d)

Copy Key

![image](https://github.com/Julius-Ulee/Daily-Weather-Report/assets/61336116/a41d2723-ad77-4b0c-b2d5-84e03de98218)

### Create a repository secret

![image](https://github.com/Julius-Ulee/Daily-Weather-Report/assets/61336116/85ebf407-a291-48a2-a3c1-e704fb1c7b06)

### Paste your key in the secret repository

![image](https://github.com/Julius-Ulee/Daily-Weather-Report/assets/61336116/c963fa67-af17-4f4e-91a8-c63065c5555d)

### Give Action Write Permissions

![image](https://github.com/Julius-Ulee/Daily-Weather-Report/assets/61336116/388b9b02-a40c-4a52-a656-06729aa3d02b)

![image](https://github.com/Julius-Ulee/Daily-Weather-Report/assets/61336116/c87bacb0-551a-434c-bac4-85e82d412f54)

### Run the action manually

![image](https://github.com/Julius-Ulee/Daily-Weather-Report/assets/61336116/9fc923cb-6d2e-4e54-8e19-5ec4cf4d2a11)

And you're all set! From now on the repo will update your weather every 1 hour.

## Costumization
You can change your weather in `config.json` to suit where you are.
```json
{
  "city": "your city"
}
```

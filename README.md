# freepbx-weather-by-zip-3.0.0
Complete overhaul of POSSA/freepbx-weather-by-zip:master

FreePBX module, reads back weather forecast from dtmf zip code input. Tested working on FreePBX17 &amp; Debian 12
This script automatically installs all the necessary files along with the Weather by ZIP module.
Tested and working on FreePBX17 on Debian 12

█████ QUICK START GUIDE █████

cd /tmp

wget https://github.com/user-attachments/files/22192815/install_weather.sh

sudo chmod +x install_weather.sh

sudo ./install_weather.sh


1️⃣ SET YOUR API KEY (Required!):
weather-setkey YOUR_API_KEY

Don't have a key? Get one free:
• Go to: https://openweathermap.org/api
• Click 'Subscribe' → Choose FREE plan
• Sign up (takes 1 minute)
• Copy your API key
2️⃣ TEST YOUR SETUP:
test-weather

3️⃣ USE THE SERVICE:
Dial *947 from any phone
Enter any 5-digit US ZIP code

============================================================

📋 AVAILABLE COMMANDS:
weather-setkey YOUR_KEY - Set API key
test-weather [ZIP] - Test the weather API
weather-fix - Quick fix if issues

📊 TROUBLESHOOTING:
• Check logs: tail -f /tmp/weather_agi.log
• Verify key: weather-setkey
• Test API: test-weather 10001
• Quick fix: weather-fix

🌐 WEB INTERFACE:
Admin → Applications → Weather by ZIP

[install_weather.sh](https://github.com/user-attachments/files/22192815/install_weather.sh)

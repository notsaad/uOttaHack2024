# uOttaHack 2024 Project: Sustain

![leaf_icon-removebg-preview(1)](https://github.com/user-attachments/assets/cc50d587-eb5b-4177-a5f5-2214e4ee4a3e)


[Demo Video & Devpost Listing](https://devpost.com/software/sustain-5z8wkg)

## How It Works:
1. The user takes an image of a clothing tag on the app.
2. That image is broken down into metadata, and sent to the Flask endpoint.
3. The Flask endpoint then sends the metadata to the Google Vision AI API which scans it for readable text.
4. This readable text is sent back to the Flask endpoint to be used in the backend algorithms to calculate emissions.
5. Based on a variety of factors (country of origin, manufacturer, material makeup) a sustainability score is calculated, and send to the endpoint in the form of JSON.
6. This JSON is then unpacked and displayed in the app for the user to see.

## Technologies Used:
- Flask
- Python
- Google Vision AI API
- React Native
- JavaScript

# Blynk
In this workshop, you will learn how to control an LED from an App.

1. You will need to install "Blynk" app on your smart phone/iPad.
![findapp](https://user-images.githubusercontent.com/11530521/53096735-60416680-3552-11e9-9933-508454d549b1.png)

2. Create Blynk account.
![createacc](https://user-images.githubusercontent.com/11530521/53096769-74856380-3552-11e9-80c8-556b3a6d9737.png)

3. Connect an LED to NodeMCU (PIN GPIO3) with a resistor and connect ground
![ledblynk](https://user-images.githubusercontent.com/11530521/53096748-66374780-3552-11e9-93b5-e4303ab0e54c.png)

4. Upload the sketch (enter your Authorization token, WiFi SSID and WiFi password)
- You will need to obtain Authorization token from Blynk app by creating a new project
- Enter project name, choose device (ESP8266), connection type (GSM or WiFi), select light/dark theme
![auth](https://user-images.githubusercontent.com/11530521/53096808-8c5ce780-3552-11e9-9e66-92d0f2d9ec47.png)
- Token is then sent to your registered email address

5. Add a widget "button"
![addbutton](https://user-images.githubusercontent.com/11530521/53096883-bf9f7680-3552-11e9-96f5-5f8c436dbc5a.png)

6. Configure the button, select "switch" and PIN "GPIO3"
![configure](https://user-images.githubusercontent.com/11530521/53096968-ea89ca80-3552-11e9-8501-e25239b14460.png)

7. Hit "Play" button and now you can turn your LED ON/OFF from your smart phone.
![final](https://user-images.githubusercontent.com/11530521/53096983-f7a6b980-3552-11e9-8729-2084f7db3749.png)

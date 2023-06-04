# ISS Tracker

This is a Python script that tracks the International Space Station (ISS) using its API and sends an email notification when the ISS is overhead and it's nighttime at your location.

## Requirements

- Python 3.x
- `requests` library (install with `pip install requests`)
- `smtplib` library (part of the Python standard library)
- Internet access

## How to Run

1. Clone the repository or download the `iss_tracking.py` file.
2. Open the `track.py` file in a text editor.
3. Modify the following variables with your information:
   - `MY_LAT`: Your latitude coordinate (e.g., 51.507351)
   - `MY_LONG`: Your longitude coordinate (e.g., -0.127758)
   - `MY_EMAIL`: Your email address
   - `MY_PASSWORD`: Your email password (or an app password if you have 2FA enabled)
4. Save the file after making the necessary changes.
5. Make sure your computer is turned on and connected to the internet.
6. Open a terminal or command prompt.
7. Navigate to the directory where the `track.py` file is located.
8. Run the script using the command: `python track.py`

The script will continuously check if the ISS is overhead and if it's nighttime at your location. If both conditions are met, it will send an email notification to the specified email address.

Please ensure that your computer remains running and connected to the internet for the script to continue checking. If the code execution is interrupted or the computer is turned off, the checks will not be performed, and email notifications will not be sent.

## Important Note

Please ensure that you have allowed access to less secure apps or generated an app password for your email account, depending on your email provider's security settings. This is necessary for the script to send the email.

## Usefulness and Background

I made this to demonstrate the usage of the ISS API and email sending in Python. It allows you to track the ISS and receive notifications when it passes over your location during nighttime.

Feel free to modify and enhance the code according to your requirements. You can explore additional features such as integrating with a notification service, logging the ISS passes, or extending the functionality to include other space-related APIs.

Please note that this script is for educational and personal use purposes and should not be used for commercial or critical applications.

## Resources

- [Open Notify API](http://open-notify.org/)
- [Sunrise-Sunset API](https://sunrise-sunset.org/)



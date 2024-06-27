# ISS Overhead Notification

This project notifies you via email when the International Space Station (ISS) is overhead at your location and it is nighttime.

## Features

- Checks the current position of the ISS.
- Determines if it is currently nighttime at your location.
- Sends an email notification if the ISS is overhead and it is nighttime.

## Requirements

- Python 3.x
- `requests` library
- `smtplib` library
- `time` library
- `datetime` library



1. Replace the following placeholder values with your actual information:
    - `MY_LAT` and `MY_LNG`: Your latitude and longitude.
    - `MY_EMAIL`: Your email address.
    - `MY_PASSWORD`: Your email password.

    ```python
    MY_LAT = 28.613939  # Your latitude
    MY_LNG = 77.209023  # Your longitude
    MY_EMAIL = "YOUR EMAIL"
    MY_PASSWORD = "YOUR PASSWORD"
    ```


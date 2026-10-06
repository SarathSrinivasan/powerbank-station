PREMIUM POWER POWERBANK FRONTEND

Files:
- index.html    Home + QR
- rent.html     Sends RENT_REQUESTED
- devices.html  Receives AVAILABILITY and lets customer select a device
- payment.html  Sends PAYMENT_SUCCESS / OPEN_SLOT
- return.html   Return placeholder

GitHub Pages:
https://sarathsrinivasan.github.io/powerbank-station/

MQTT:
Broker: wss://broker.emqx.io:8084/mqtt
Username: none
Password: none

Topics:
POWERBANK/001/RENT_REQUEST
POWERBANK/001/AVAILABILITY
POWERBANK/001/PAYMENT
POWERBANK/001/RETURN

Put all HTML files in the repository root.
Rename index.html only if your repository uses a different entry point.

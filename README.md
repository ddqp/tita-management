# TITA Management

Static HTTPS frontend for nearby TITA Pro management over Web Bluetooth.

Open https://ddqp.github.io/tita-management/ in Bluefy on iPhone. Use normal Wi-Fi or cellular internet to load this page, then select TITA Monitor and enter your device management password. Uses the F063+ full vehicle API over the existing encrypted management GATT protocol. Web version 20261018.3. Reopening needs internet; offline availability is not promised.

All settings requests travel directly over encrypted BLE between the browser and TITA. No backend, analytics, external scripts, or credential storage is used. Hosting this page does not provide remote access to a distant device. Device firmware, private keys, credentials, and backups are excluded.

Tabs: system, vehicle (full transmitter raw and decoded data), iPhone/music, CarPlay, TITA local, other. Cover-file upload remains available only through the device local HTTP interface. A selected tab does not switch the physical display until its display action is pressed.

Publish the main branch root with GitHub Pages. No custom domain required.

# Qspyders/Pyspiders/Jspiders QR Attendance Automator

A simple, fast, and automated web tool designed to generate daily attendance QR codes for Pyspiders classes. Instead of searching for your QR everyday in low network, this tool automates the date formatting and saves your details locally for instant access.

</br>
</br>

>    Direct Access ---->   https://shreyas445.github.io/QRat/

</br>

## ✨ Features

* **Daily Automation:** Automatically grabs today's date and formats the QR data exactly as required (`StudentID/YYYY-MM-DD/student`).
* **Multi-Student Support:** Save multiple friends or classmates in your collection.
* **Local Storage:** All names and student numbers are saved directly in your browser's local storage. No databases, no logins, and complete privacy.
* **Scan & Decode:** Easily add new students by scanning an existing QR code using your device's camera or by uploading an image of a QR code.
* **Clean UI:** Dark mode interface optimized for mobile devices with quick access to your saved collection.

## 🚀 How to Use

1. **Open the App:** Download the `index.html` file and open it in any modern web browser (Chrome, Safari, Firefox).
2. **Add a Student:**
   * Enter the student number manually, OR
   * Tap **Scan QR** to use your device camera, OR
   * Tap **Choose File** to upload a screenshot of an existing QR code.
3. **Save to Collection:** Click **Preview**. Check the "Save to collection" box, enter the student's name, and hit **Confirm & Show QR**.
4. **Daily Attendance:** The next time you open the app, you will see your "Saved Students" list. Just tap a name to instantly generate today's attendance QR code.

## 🛠️ Technologies Used

* **HTML5 / CSS3 / Vanilla JavaScript**
* [qrcode.js](https://davidshimjs.github.io/qrcodejs/): For generating the daily QR codes.
* [html5-qrcode](https://github.com/mebjas/html5-qrcode): For scanning QR codes via the device camera.
* [jsQR](https://github.com/cozmo/jsQR): For decoding QR codes from uploaded images.

## ⚠️ Disclaimer

This is a totally unofficial tool built for convenience to automate daily QR generation. Ensure that your student ID is entered correctly so your attendance is registered properly.

# 🚀 Flet Post Notification

A Python project demonstrating how to send notifications in mobile apps using Flet and Pyjnius. It seamlessly integrates native Android notifications, handles permission management, and supports Android 13+. Build and run the app to experience native notifications in your Flet projects!

# 📽️ Demo Video

Watch the full tutorial on YouTube:How to Send Notifications in Flet using Pyjnius

# 🛠️ Installation

Make sure you have Python 3.9+ and Flet installed.

pip install flet pyjnius flet-permission-handler

Clone the repository:

git clone https://github.com/yourusername/flet-post-notification.git
cd flet-post-notification

# 🚀 Usage

Update the pyproject.toml file with required permissions.

Run the application:

flet run src/main.py

Build the APK:

flet build apk

Install and test on your Android device.

# 📂 Project Structure

flet-post-notification/
├── src/
│   ├── main.py                # Flet UI and interaction logic
│   ├── notification.py        # Notification sending functions
├── pyproject.toml             # Project configuration and 
├── README.md                  # Project documentation
└── LICENSE                    # License file

# 📝 Configuration

Update the pyproject.toml file with necessary Android permissions:

[tool.flet.android.permission]
"android.permission.ACCESS_NOTIFICATION_POLICY" = true
"android.permission.POST_NOTIFICATIONS" = true
"android.permission.WAKE_LOCK" = true
"android.permission.FOREGROUND_SERVICE" = true
"android.permission.INTERNET" = true
"android.permission.RECEIVE_BOOT_COMPLETED" = true
"android.permission.REQUEST_IGNORE_BATTERY_OPTIMIZATIONS" = true
"android.permission.SCHEDULE_EXACT_ALARM" = true
"android.permission.SYSTEM_ALERT_WINDOW" = true
"android.permission.VIBRATE" = true

# ⚙️ Troubleshooting

Notification not appearing:

Check if the POST_NOTIFICATIONS permission is granted.

App crash on Android 13+:

Ensure that the permission is explicitly requested and accepted.

No vibration:

Add the VIBRATE permission to the config file.

# 🤝 Contributing

Contributions are welcome!

Fork the project

Create a new branch

Make your changes

Submit a pull request

Feel free to open issues for bug reports or feature requests.

# 📄 License

This project is licensed under the MIT License. See the LICENSE file for details.

# 🌟 Support

If you find this project helpful, please give it a star!For more tutorials, subscribe to IT Academy on YouTube!YouTube Channel

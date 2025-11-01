# Creating Hello World APK with Kivy
The provided code is a minimal example of a Kivy application in Python. It defines how to create and launch a simple GUI app that displays the text "Hello, World!" on the screen using a label.
Setting Up Your Build EnvironmentEnsure Python, Kivy, and pip are installed.Install Buildozer, which you will use to create the APK:
# pip install buildozer
For Linux users, install additional dependencies as needed (for example, OpenJDK, git, zip, etc.).Initializing Your Project for AndroidIn your project directory (where main.py lives), initialize the Buildozer configuration:
# buildozer init
Building and Running the APKConnect your Android device via USB (with developer mode enabled), or just build the APK file:
# buildozer -v android debug

This workflow gives you a basic "Hello World" APK built with Kivy on Android
<img width="979" height="1218" alt="Image" src="https://github.com/user-attachments/assets/9f5eaeb5-5a73-412d-a655-99c6c1e9c210" />
![Image](https://github.com/user-attachments/assets/780e0036-7ebc-4053-b31f-3086f4aad316)

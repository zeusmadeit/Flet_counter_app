![image](./assets/flet-home.png)

# Flet_counter_app
A Flet counter application built using python. Flet enables developers to easily build realtime web, mobile and desktop apps in Python, No frontend experience required.

## What is Flet?
Flet is a framework that allows building interactive multi-user web, desktop and mobile applications 
in your favorite language without prior experience in frontend development.

You build a UI for your program with Flet controls which are based on Flutter by Google. 
Flet does not just "wrap" Flutter widgets, but adds its own "opinion" by combining smaller widgets, 
hiding complexities, implementing UI best-practices, applying reasonable defaults - all to ensure 
your apps look cool and professional without extra efforts.

## Instructions on how to run the app
To run the app install flet module:
```
pip install flet
```
and run the program:
```
python3 app.py
```
The app will be started in a native OS window - what a nice alternative to Electron!

## Screen Shots
![Screenshot 2024-03-22 100519](./assets/Screenshot%202024-03-22%20100519.png)


![Screenshot 2024-03-22 100646](./assets/Screenshot%202024-03-22%20100646.png)

Now, if you want to run the app as a web app, just replace the last line in the app.py file with:
```
ft.app(target=main, view=ft.AppView.WEB_BROWSER)
```

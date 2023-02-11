# House-Price-Estimator


This is a supervised learning model to predict the values of house prices based on a bunch of parameters that we give

Data Source: Open Source Data



The deployed model can be found at:
https://qrco.de/bdi0DE


Reference for deploying video: https://www.youtube.com/watch?v=oOqqwYI60FI&list=PLZoTAELRMXVOAvUbePX1lTdxQR8EY35Z1&index=4

Steps:
1. Download WinSCP, Putty and Puttygen
2. Generate .pem file
3. Use Puttygen to convert .pem to keys
4. Create SSH link with Putty
5. Use keys created to link Putty with aws and to access the repo directory on aws programatically.
6. Use putty to sudo apt-get update && sudo apt-get install python3-pip
7. Use putty to pip3 install -r requirements
8. python3 app.py

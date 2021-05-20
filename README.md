# CoWIN vaccination slot availability using Python

Script to check the available slots for Covid-19 Vaccination Centers from CoWIN API in India. This CANNOT book slots automatically. The Indian Government had blocked the API for crawlers, but we are good to go.

<!---
[Click to view the Website](https://bit.ly/3eQkvgl)
[Click to view the Website](https://bit.ly/3ob9l94)
-->

The [CoWin API](https://apisetu.gov.in/public/marketplace/api/cowin) currently states : "Further, these APIs are subject to a rate limit of 100 API calls per 5 minutes per IP". I tried deploying the Web Application but the API is blocking the request. You can easily run the web application on your machine by following the steps mentioned below.
&nbsp;

# Installing Python
Python is a programming language that is powerful but easy to learn. It is free, platform-independent, and popular among scientists.

## Recommended Method: Anaconda
The Anaconda Python distribution is an easily-installable bundle of Python and many of the libraries used throughout this class. Unless you have a good reason not to, we recommend that you use Anaconda.

### Mac/Linux users
1. Download the [appropriate version](https://www.anaconda.com/products/individual) of Anaconda
2. Follow the instructions on that page to run the installer
3. Test it out: open a terminal window, and type ``python``, you should see something like
```
Python 3.8.3 (default, Jul  2 2020, 17:30:36) [MSC v.1916 64 bit (AMD64)] :: Anaconda, Inc. on win32
```
If `Anaconda` doesn't appear on the first line, you are using a different version of Python. See the troubleshooting section below.

1. Test out the IPython notebook: open a Terminal window, and type `ipython notebook`. A new browser window should pop up.
2. Click `New Notebook` to create a new notebook file
3. Update IPython to the newest version by typing `conda update ipython` at the command line

### Windows Users
1. Download the [appropriate version](https://www.anaconda.com/products/individual) of Anaconda
2. Follow the instructions on that page to run the installer.
3. Go to Start and Run Jupyter Notebook.
4. Click `New Notebook`, which should open a new page.

# Usage
- Clone the repository. using ```bash ! Git Clone https://github.com/Puneesh6280/Cowin-vaccine-tracker.git ```
- The tool only works with Indian IP addresses so disconnect your VPN if needed.
- Enter the command - ``` bash cd Cowin vaccine tracker```
- Install all the dependencies - ```bash pip install -r requirements.txt```
- Run Anaconda Promt (Run as Administrator) From Start Menu.
- Go to your Directory Eg ``` bash cd Cowin vaccine tracker```
- Run `streamlit run app.py`

-   You can now view your Streamlit app in your browser.

  Local URL: http://localhost:8501
  Network URL: http://192.168.1.7:8501




  <h1 align="center">Hi 👋, I'm Puneesh Gogia</h1>
  <h3 align="center">A passionate Python developer from India</h3>

  - 🌱 I’m currently learning **Tensorflow**

  - 👨‍💻 All of my projects are available at [https://github.com/Puneesh6280](https://github.com/Puneesh6280)

  - 📫 How to reach me **puneesh.gogia15@gmail.com**


  <h3 align="left">Languages and Tools:</h3>
  <p align="left"> <a href="https://www.arduino.cc/" target="_blank"> <img src="https://cdn.worldvectorlogo.com/logos/arduino-1.svg" alt="arduino" width="40" height="40"/> </a> <a href="https://www.figma.com/" target="_blank"> <img src="https://www.vectorlogo.zone/logos/figma/figma-icon.svg" alt="figma" width="40" height="40"/> </a> <a href="https://opencv.org/" target="_blank"> <img src="https://www.vectorlogo.zone/logos/opencv/opencv-icon.svg" alt="opencv" width="40" height="40"/> </a> <a href="https://www.python.org" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> </p>

  <p><img align="left" src="https://github-readme-stats.vercel.app/api/top-langs?username=puneesh6280&show_icons=true&locale=en&layout=compact" alt="puneesh6280" /></p>

  <p>&nbsp;<img align="center" src="https://github-readme-stats.vercel.app/api?username=puneesh6280&show_icons=true&locale=en" alt="puneesh6280" /></p>

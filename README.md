# Youtube_Api_Analysis
This project was created to analyze data using the YouTube API. It retrieves information from YouTube videos, channels, and playlists to perform detailed analysis. By interacting with the API, the project allows users to collect and process video metrics. The goal is to provide insights into video performance and trends. It serves as a tool for anyone looking to analyze YouTube data effectively.

# Getting your API Key

First, you need to obtain your API key.
Follow the link below, it will help you if you have any questions.
### [YouTube API Tutorial | For Beginners](https://www.youtube.com/watch?v=XEZYadc2o-8)

Or you can also check th documentation.

### [YouTube Data API Overview](https://developers.google.com/youtube/v3/getting-started)

# Creating .env file
To keep your API key protected, you are going to use a .env file, and only you will have access to it.
Anyone who wants to run this project needs to follow these steps.

Open your terminal and execute the following command:

    pwd


If you are in the wrong path, go to the correct one using:

    cd /your_path_project

This will check the path. If the path is correct, execute:

    touch .env
    
Open your .env file using the following command:

    nano .env

Copy and paste your API key into the .env file and close it.

    API_KEY=your_api_key_here

This step is done.

# Setting up the environment

Installing a virtual environment

    pip install virtualenv

Creating your virtual environment

    python3 -m venv venv

Activating your virtual environment

    source venv/bin/activate

You can deactivate it by running:

    deactivate

Installing all dependencies

    pip install -r requirements.txt

After these steps, you can run your project using the following command:

    jupyter lab

or use your favorite IDE.

# Important

Once the process is done the first time, you just need to open your folder, activate the virtual environment, and open your IDE.

I just tested the project on Linux.

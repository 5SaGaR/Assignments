# Steps to run the Crew 

Create a Python virtual environment first after clonining the project (python -m venv venv) then activate venv(name accordingly) (.\venv\Scripts\activate)

Add .env file in project directory where you should declare API keys of services used as environment variables

Install dependencies by running pip install -r requirements.txt

Run the app by using(python app.py) command 

As the app currently uses cohere API it is a bit slow at inference inference speed can be improved by using any other framework other than Crewai or you can change model to use groq API or cohere 'command-r' model for faster inference

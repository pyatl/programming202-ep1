# programming202-ep1
using virtual environments and pip.


## Instructions

Download the code from github

Create a new virtual environment by going to the folder or directory where you downloaded the code to and running:

`python3 -m venv .venv`

Then activate the environment.

On OSX / Linux: `source .venv/bin/activate`

On Windows: ` .venv/Scripts/activate.bat`

Install the required libraries: `pip install -r requirements.txt`

Run the code: `uvicorn main:app --reload`

Visit [http://127.0.0.1:8000](http://127.0.0.1:8000)
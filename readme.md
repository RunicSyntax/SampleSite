## Running the website

### Setting up the environment

To the run the website we must first set up the environment. This can be done by first creating a virtual environment by running the following in the terminal.
> python -m venv .venv

Next we must activate the environment, for Windows run the following command
>.\.venv\Scripts\activate

For macOS or Linux run
>source .venv/bin/activate

Then install the necessary packages using pip install
>pip install -r requirements.txt
 
### Running the website on localhost

Since this project uses the Django framework, all we have to do is run 
>python manage.py runserver

Then by clicking the link it provides in the terminal you can access the website.
_Hack the North: SurveyMonkey’s API Challenge Winner_
Project Name: Just-Your-Feedback

Video of project
https://www.youtube.com/watch?v=BxJxPFECzqQ

Project Summary:
Based on SurveyMonkey’s Developer API Challenge, our group has created a Machine Learning Model which can be utilized by end-users to automate the submission of Survey responses. The machine learning algorithm was imported using the ImageAI Python Library. Using this library, we were able to train the Machine Learning model using Supervised Learning with 500+ images. After several implementations and re-iterations, the model was able to recognize hand gestures from the user. Our live-demonstration displays a Survey for user's experience with Hack the North Hackathon. Based on the user's hand gesture response on the embedded webcam, an automated submission is made and recorded. 

Extra Notes about project: 
We used a Python library called ImageAI, which is useful for generating image recognition models based off of machine learning. In order to create an accurate model, we needed to take over 500 photos of the two different thumb states for model training and an additional 100 photos for model testing. We used the SqueezeNet algorithm to generate our image recognition model. The training process took well over 5 hours as it was our first time working with image recognition and finding the best algorithm to use. Originally, we wanted to train the model to recognize human hands, but due to the limited time constraints of the hackathon we opted for the simpler paper hands instead. Once the model was created, a new image can be compared against the model which will output a probability for each thumb state.

The SurveyMonkey API was quite easy to learn as it was very well-documented. We used Postman to easily test out some API calls and did not run into any problems. We were able to make successful API calls automatically which would create a new response to a survey. We were also hoping to display survey result data on our web application, but due to lack of time we kept it simple.


Technologies Utilized:
Python, Pyramid (Web Framework), ImageAI (Python Library for Machine Learning Algorithms), JavaScript, HTML, CSS, JSON, SurveyMonkey's Developer API.

Developer Notes:
Activate the virtual environment by running `source pyenv/bin/activate` from the project root.
**NOTE: To leave a virtual environment, simply run `deactivate` from within the virtual enviroment.**

## Install Requirements
Run `pip install -e .`. This installs all the Python packages specified in the `setup.py` file.

## Run Waitress Server
Run `pserve development.ini --reload`. 

# MicroserviceA

A. Clear instructions for how to programmatically REQUEST data from the microservice you implemented. Include an example call.

To programmatically request data fr the microservice I implemented, clone this repository. Once you have done that you must install the dependencies with in the current working directory.
``pip install fastapi uvicorn requests`` 
once you have done this successfully, you can run the microservice implementation with 
``unicorn main:app --reload --port 8001``
open the URL(TRIVIA_API_URL = "https://the-trivia-api.com/api/questions?limit=1") in your browser.
You can then request (data) a new set of questions and options by hitting the refresh button in your browser. 

B. Clear instructions for how to programmatically RECEIVE data from the microservice you implemented.
Furthermore, to implement this into your own program you can include the URL in main in your own program. From there you can extract the data syntactically as you wish. I included a "test_program.py" as an example for you to reference if necessary. This will receive the data from the API. 

C. UML sequence diagram showing how requesting and receiving data works. Make it detailed enough that your teammate (and your grader) will understand.

<img width="555" alt="Screenshot 2024-05-20 at 11 26 44 PM" src="https://github.com/Drones507/MicroserviceA/assets/114556741/4e9e395b-eeeb-4195-b701-8e83987cd6bc">

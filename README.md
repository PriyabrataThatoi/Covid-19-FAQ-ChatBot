# SARATHI : A Covid 19 FAQ ChatBot & Medical Facilitator

SARATHI is a RASA NLU powered chatbot that takes user inputs and responses in return. The chatbot uses the SpaCy language model to matches the user input with the intent repository. It also call s API (https://data.medicare.gov/resource/{}.json) to look up medical facilities based on the location and medical facility type provided


![Rasa NLU](https://user-images.githubusercontent.com/54467567/87466478-ec3aaf00-c5db-11ea-976e-160d700afb17.png)


## The Process:

![Rasa Process](https://user-images.githubusercontent.com/54467567/87466557-17250300-c5dc-11ea-94ca-5b0864f982bb.png)

## Files Used:

#### NLU.MD : it contains all the intents of the users
![Intent](https://user-images.githubusercontent.com/54467567/87467296-59027900-c5dd-11ea-99b9-2bb71daa56f9.PNG)

#### STORIES.MD : It contains all the path the user might take (happy path, sad path, etc.)
![Story](https://user-images.githubusercontent.com/54467567/87467298-59027900-c5dd-11ea-9cbe-f0cfbc2b9a78.PNG)

#### CONFIG : It contains all pipelines & policies
![config](https://user-images.githubusercontent.com/54467567/87467292-5869e280-c5dd-11ea-85da-17b9e326a6dc.PNG)

#### DOMAIN : It contains all the reponses and the flow of the chat
![Domain](https://user-images.githubusercontent.com/54467567/87467293-59027900-c5dd-11ea-97fc-f261267b32da.PNG)

#### ACTION : It contains the user actions based on the input stored in the slots
![Action](https://user-images.githubusercontent.com/54467567/87467291-57d14c00-c5dd-11ea-8de4-2916a3eb7927.PNG)


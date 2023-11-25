# Habitat_Hackers
The file consolidates all the working files and final submission code for the Habit Hackers - Project Rewild.

## Github repos
### Azure AI Search
https://github.com/Katk-99/rewild  - code that calls the Azure AI Search, Bring Your Own Data function
See youtube video for details and Demo at the end

### In-progress development of user app
https://github.com/prashantinim/Test.git - ios application using swift 

https://github.com/prashantinim/Rewild.git - same ios application but with openai integration 

https://github.com/prashantinim/Rewild-.git - webapp with open ai

### data pipepile for data used in other repos
https://github.com/eenventer/rewild_db/wiki/Developer-Setup   - 


## Challenges
The key challenge has been in deploying the Azure AI Search into a user applications. Our attempts so far have been unsucessful though other AI API integrations such as the standard OpenAI integration does work in these apps.

We think the failure of the Azure AI Search integration is due to the complexity of the API calls (two API calls - one to Open AI and another to the Azure Search Endpoint to access our indexed data and feed it into OpenAI) and the fact that this capability is still in preview.

Happy reading!

The Habitat Hackers Team

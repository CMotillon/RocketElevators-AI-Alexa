# Rocket Elevators AI with Alexa

## How Alexa Skills Work

An Alexa skill has both an interaction model—or voice user interface—and application logic. When a customer speaks, Alexa processes the speech in the context of your interaction model to determine the customer request. Alexa then sends the request to your skill application logic, which acts on it. You provide your application logic as a back-end cloud service hosted by Alexa, AWS, or another server.


## Skill Invocation Name

> Rocket Elevators

## Custom Intents and Utterances

> **OptionIntent**
>  - "i'm  not  sure"
>  - "i  don't  know"
>  - "options"
>  - "what are my options"

> **RocketElevatorsStatusReportIntent**
>  - "briefing"
>  - "summary"
>  - "status update"
>  - "rocket elevators status update"
>  - "what is going on at rocket elevators"
>  - "what's going on at rocket elevators"

> **ElevatorStatusIntent**
>  - "{id}"
>  - "id {id}"
>  - "elevator"
>  - "elevators number {id}"
>  - "elevator id {id}"
>  - "elevator {id}"
>  - "i. d. {id}"
>  - "what's the status of elevator {id}"
>  - "elevator {id} status"
>  - "status of elevator {id}"
>  - "what is the status of elevator {id}"

## Dialog Delegation Strategy

If you are trying to get the status of an elevator and fail to provide the id of the elevator, you will be prompted by Alexa to provide and id before continuing.

> "What  is  the  ID  of  the  elevator  you  would  like  the  status  of?"

# Week 13 Team Members

- [Cedric Motillon](https://github.com/CMotillon) (Team Leader) - Google DialogFlow ChatBot
- [Abdul Akeeb](https://github.com/thisfncodeio) - Amazon Alexa
- [Jean-Francois Taillefer](https://github.com/lamach1n3) - Microsoft Azure Cognitive Services
- [Lionel Niyongabire](https://github.com/lioniyon) - Microsoft Azure Cognitive Services
- [Jeremy Augustin](https://github.com/JJdoubleA) - Microsoft Azure Cognitive Services




## Creating Chatbot using Dialog Flow

## Dialog Flow:
•	It is basically defined as a Google service which operates on a Google Cloud Platform.

•	It is also defined as an NLP (Natural Language Processing) platform, which is used to develop an application related to the conversations and experience for the customers of the company in different languages on numerous platforms.

•	It is mainly used to build actions for most of the Google Assistant devices.

•	By using Google-powered products developers can design text-based and voice-conversation interfaces in order to answer the queries of customers in various languages. 

•	Ex: Various companies use Dialog flow to make messaging bots that reply to the queries of the customers on different platforms such as Google Assistant,Facebook Messenger,Alexa Voice Search (AVS) etc.

## Components of Dialog Flow:

Agent:
It is defined as a virtual agent whose task is to manage the end-user conversations.

Intent:
Intent comprises logic and elements to parse the information of the user. It helps to map what the users are saying with the responses. There are various components in the intent, such as events, response, the user says, contexts, and action.

Entity:
Entity is defined as a knowledge repository that is used by the agent to answer the questions of the user. There are various types of system entities, such as weather, location, date, etc.

## Create Chatbot using Dialog Flow:
1) First, we have to log in to the Dialogflow. We can log in to the Dialogflow by using the link https://dialogflow.cloud.google.com/#/getStarted


2) The interface looks like
![image](https://github.com/swarupa22/Chatbot-using-DialogFlow/assets/134698070/f1f0be54-c25c-4f47-b26a-deae98782706)


3) Next, we have to click on the create agent to create a new agent. The interface looks like 
![image](https://github.com/swarupa22/Chatbot-using-DialogFlow/assets/134698070/28bcc014-4d4b-46b0-a97c-b9ecee7c4585)


4.Fill the details like language, the default time zone, and the name for your new bot.Click on create,now the agent is successfully created.This will redirect you to the new page 
![image](https://github.com/swarupa22/Chatbot-using-DialogFlow/assets/134698070/d019aa77-77bc-4e0e-83ae-5c24d8830d29)


5.SmallTalk Section:
![image](https://github.com/swarupa22/Chatbot-using-DialogFlow/assets/134698070/c2218480-d59f-42c2-b38e-03dc552687ce)


Fill up the questions which are asked in each part with your own answers.


6.The next step is creating an intent. The intent page looks like  
![image](https://github.com/swarupa22/Chatbot-using-DialogFlow/assets/134698070/6cf9bb08-2312-45d4-8ca9-82c75eaeeba1)


Next, we have to add some content to training phases, and these will be in the text form and then click on the enter button.


![image](https://github.com/swarupa22/Chatbot-using-DialogFlow/assets/134698070/8172c229-d8a3-4ab5-b451-22e11d9822a2)


7.Next, we have to go down on the option named Responses and remove or delete the existing ones. Click on save button
![image](https://github.com/swarupa22/Chatbot-using-DialogFlow/assets/134698070/6a950058-a9c6-483c-b0d5-057292b723c5)


8.Then, click on the ADD RESPONSES, and then we have to click on the Text response Then type the response which you want.
![image](https://github.com/swarupa22/Chatbot-using-DialogFlow/assets/134698070/4023bc7e-4eac-4c30-9a99-60364bde422f)


9.In the Action and parameters table, the Dialogflow creates a row, which is present below the Training phrases.
![image](https://github.com/swarupa22/Chatbot-using-DialogFlow/assets/134698070/b5addc9c-dca0-46e7-9858-2c77face83a4)


10.Other than this, we will be having a list of questions. So, to handle this, you can create a custom entity.


11.We have to click on the button add entity +, on the left sidebar menu to the Entities. Click on create, now the entity is successfully created.


12.Then you need to give entity name. Now add the entities in the below edit section. Click on save button.
![image](https://github.com/swarupa22/Chatbot-using-DialogFlow/assets/134698070/6922cb77-bb06-4b51-8fd2-3b9a64382f6e)


13.Now,if you want to make the use of the new entity, then you have to add the training phrases to the entity which is created. 


14.Click on the option named 'Intents', which is present on the left sidebar menu. Then, click on the intent fashionBot.
![image](https://github.com/swarupa22/Chatbot-using-DialogFlow/assets/134698070/170ff980-1ad8-45e3-bd00-523a7e0a3af1)


15.Next, you have to add the various training phrases and follow the same process which we followed in intent step.


16.After completion of process, click on Add follow-up intent which is over the intent.
![image](https://github.com/swarupa22/Chatbot-using-DialogFlow/assets/134698070/44b00c43-17c4-4216-be4f-c974c3cfdaee)


17.Then from the list appeared select what you wish to add.
![image](https://github.com/swarupa22/Chatbot-using-DialogFlow/assets/134698070/a4bc8f59-796b-4253-b7bb-af0512d2f814)


18.Edit the responses for yes and no.


19.In the training section, it contains the data which we used for training.


20.In the validation section, we can create our own custom data for validation. We can fix the errors here.


21.In the history section, it will record our data


22.In the analytics section, it will tell us what is used, from where it is used.


23.In the pre-built agents, it contains the operations or agents which are pre-built they are already trained with different variety of responses.


24.In the bot settings, we can also import the example file to our agent.


25.click on the setting icon, which is present next to the agent name.
![image](https://github.com/swarupa22/Chatbot-using-DialogFlow/assets/134698070/2411b410-a79d-4f78-b662-168833091bf5)


26.Choose the Export and Import. Select an option from export as zip,restore from zip,import from zip.
![image](https://github.com/swarupa22/Chatbot-using-DialogFlow/assets/134698070/a09fabf7-fe70-4d19-817c-f284661a78e7)


27.Go to Integration section , click webdemo from text-based part
![image](https://github.com/swarupa22/Chatbot-using-DialogFlow/assets/134698070/50f82af5-8f62-45c0-8770-eb2c583222ff)


28.Click on web demo .Click on the link given.You will redirect to new tab.
![image](https://github.com/swarupa22/Chatbot-using-DialogFlow/assets/134698070/4bee4a08-45d8-456c-a351-5ee62b217594)


29.Using Web Server:
![image](https://github.com/swarupa22/Chatbot-using-DialogFlow/assets/134698070/e33528a7-3393-4b56-a2b2-dabfa47def75)


![image](https://github.com/swarupa22/Chatbot-using-DialogFlow/assets/134698070/69dd10f3-5dc1-4ffc-b329-f611eb7890ac)






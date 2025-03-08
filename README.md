Highlights and steps taken in the LLM Response Filtering project:-
1) The below is model uses Facebook's blenderbot to generate responses to user text. I started off with this and later realized that it can only give proper responses for questions and conversations.

2) So I though of adding a model which will factually check the authenticity of the response. But then I hit another problem where the model could give a confident response even for some things that it knows very little about.

3) So I decided to rate the model's response through a confidence threshold and whatever response which has a confidence score below the threshold will be discarded and then replace with "I don't know".

4) The reason to work on this particular problem is because I feel like the halucination caused by these models will create a lot of damage to infromation in the society in future. As more people start to use these chatbots, the top 1% wealthy might take advantage of the misinformation and then can move things in the way they wanted.

5) By implementing these methods we can be able to atleast say that an infroamtion that the chatbot provides is true or not. That is the reason why I later used Wikipedia to enable our conversational model to generate factual responses.

6) The project is under development...... I am now currently figuring out how to add context window to the chatbot within the program to be able to remember what the user asked and what it told the user. Also I am planning to include some filters in the user's question or context which is harmful in nature.

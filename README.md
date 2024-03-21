# aws-solution-architect-associate-training
Repository for the AWS training and preparing for the exam 
![image](https://github.com/AzaBor23/aws-solution-architect-associate-training/assets/123963873/1032ed92-2a5e-439d-87a0-a3a7137cfbe6)
A client/user asks questions to the chatbot through an application that is hosted through AWS Amplify and Amazon CloudFront.
The question is sent to the AWS Lambda RAG function through Amazon API Gateway.
To retrieve the relevant context from the document source, the RAG function calls the Amazon Kendra API.
The RAG function then sends the API returned content, along with a prebuilt prompt, to the foundation model (FM) in Amazon Bedrock.
The FM returned response is then sent back to the client/user.

# AWS-Bedrock-LLMServerlessApp
LLM app using AWS Bedrock ( credits : [www.learn.deeplearning.ai](https://www.deeplearning.ai/))
## POC Overview And High Level Design

- Use of AWS-Bedrock to levarage a common problem of customer service department in handling a customer issue with their compnay's product or service.
    - Create a base LLM app which uses jupitor notebook and AWS Bedrock to generate a  response for a given "prompt".
    - Use a sample audio file , transcribe using AWS transcribe service and feed it to AWS Bedrock to solve a business problem( in this case summarize the call/determine if there is any problem that customer is having and enerate a alert if the issue is urgent)
    - Below is the high-level Work flow /Architecture diagram.
       ![High Level Design](./images/Bedrock_LLM_0.jpg)



### Overview of the code:
- 




#### Below AWS service  were used
- AWS Lambda ( serverless)
- S3
- Bedrock
- AWS transcribe service

Note: This code under src can be run using Jupyter python notebook.
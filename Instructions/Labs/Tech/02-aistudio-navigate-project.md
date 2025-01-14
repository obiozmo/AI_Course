# Navigate Azure AI Project Options

This guide helps you navigate through the different options within your Azure AI Project.

**Duration: 10 to 15 minutes**

## Project Overview

Start by returning to the build section and selecting your project.

![Project View AI Studio](../../media/aistudio-project.png)

### Key Sections in Your Project

1. **Overview**: A general overview of your project's status and settings.
2. **Tools**: Tools available for your project:
   - **Playground**: Test your model and chat session here.
   - **Evaluation**: Evaluate model performance with standard metrics to choose the best version for your needs.
   - **Prompt Flow**: A development tool for streamlining AI application development with Large Language Models (LLMs).
   - **Custom Neural Voice**: Design a unique voice persona and manage voice talents, datasets, models, tests, and endpoint connections.
3. **Components**: Essential components for your project:
   - **Data**: Import data for your models.
   - **Indexes**: Create indexes to customise generative AI responses.
   - **Deployments**: Set up the deployment infrastructure for external model consumption.
   - **Content Filters**: Manage content filtering configurations that work alongside core models.

## Deployments

Before utilizing the playground, you need to create a deployment.

1. **Create a New Deployment**:
   ![Create Deployment](../../media/azure-ai-deployments-create.png)

   - Select Real-Time Endpoint
      ![Real-Time Endpoint](<../../media/ai-studio-navigate/real-time endpoint.png>)
  
   - Select the model you wish to deploy, any gpt model will work correctly for the course.
  
     ![Select Model](../../media/ai-studio-navigate/select-model.png)


   - Confirm and deploy the model.
  
     ![Create Deployment Deploy](../../media/azure-ai-deployments-create-gpt4-create.png)

   - Leave the options in the following window by default and click Deploy.
      ![Default Options](../../media/ai-studio-navigate/default-options.png)
  

2. **Repeat for Additional Models**:
   - Select another model.
  
     ![Create Deployment Select Model](../../media/ai-studio-deploy-gpt35-find.png)


   - Select the model you wish to deploy, any gpt model will work correctly for the course.

      ![Select Model](../../media/ai-studio-navigate/select-model.png)

    > **Note**: Creating multiple models can help manage heavy traffic and provide alternatives.

3. **Navigate to the Playground**:
   ![Create Deployment Navigate to Playground](../../media/azure-ai-deployments-create-gpt4-openplayground.png)

    > **Tip**: Deploying multiple models is useful for testing solutions and choosing the right model.

## Using the Playground

The *Chat* playground offers a chatbot interface for your deployment models, utilising the *ChatCompletions* API.

1. **Explore Options**: Familiarise yourself with various features in this section. We will delve into more details in the next exercise.

    > **Info**: The top right corner of the playground displays the API in use.


## Grounding

As discussed previously, grounding ensures responses are based on real-world knowledge from extensive training data, but limitations exist due to data cutoff dates and potential inaccuracies from training patterns.

Using the following prompt:

What is your cutoff date? what's the latest information you have been trained on?



![Grounding](../../media/ai-studio-navigate/grounding.png)
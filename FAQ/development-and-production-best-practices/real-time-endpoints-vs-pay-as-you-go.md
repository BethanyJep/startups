# What model deployment should I use and why in AI studio? 
<!-- <iframe width="560" height="315" src="https://www.youtube.com/embed/4sfHaklrKBI?si=8-yerPa-swzeJ0Yr" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe> -->

 There are different model deployment options in AI Studio, including real-time endpoints, Azure-hosted models, and custom-built infrastructure. Model deployment in AI Studio offers options like deploying models from a catalog or as a service on Microsoft Azure, each with different cost structures and features. 

## Real-time endpoint deployment 

Deploying models using a real-time endpoint from a catalog in AI Studio provides access to models from various sources like Microsoft, OpenAI, Mistral, Llama and Hugging Face, allowing direct deployment at real-time endpoints based on token usage. 

Using a real-time endpoint for model deployment offers several advantages: 

- Direct Deployment: Models can be deployed directly at a real-time endpoint, allowing for immediate access and usage. 

- Cost Efficiency: With this deployment method, you only pay for the tokens that you consume, making it a cost-effective option. 

- Flexibility: You have the option to add additional content or safety features separately if needed. 

Custom Infrastructure: If you have your own models and infrastructure, deploying them with a real-time endpoint allows you to build on your existing infrastructure, providing more control and customization options. 

## Model-as-a-Service 

The Azure-hosted model deployment option involves hosting the model on Azure GPUs, where you only pay for the infrastructure, you use. On the other hand, building your own infrastructure to host the model means you will be responsible for the infrastructure costs associated with hosting the model. 

Alternatively, deploying models as a service on Microsoft Azure involves using model endpoints and GPU hosting, with costs primarily based on token consumption and the option to add safety features separately. 

## Real-time endpoint deployment vs Model-as-a-service 

When choosing between the available model deployment options in AI Studio, you should consider the following factors: 

- Usage: Decide based on how you plan to use the model. Different deployment options are available based on your usage requirements such as embedding models, chat models and image generation models. 

- Cost: Consider the cost implications of each deployment option. For example, with real-time endpoints, you will only pay for the tokens you consume. 

- Infrastructure: Evaluate whether you want to host the model on Azure or build your own infrastructure. Hosting on Azure means using their GPU resources, while building your own infrastructure incurs costs for hosting. 

- Customization: Consider whether you need to add any safety features or customize the deployment in any way. This may influence your choice of deployment option. 

By considering these factors, you can make an informed decision on which model deployment option is best suited for your specific needs in AI Studio. 

## Conclusion 

In summary, whether you opt for the model catalog, Models-as-a-Service, or hosted infrastructure, Azure AI Studio provides flexibility and security for deploying models tailored to your specific needs. 
OpenAI, or Generative AI, is used in many Microsoft products. Therefore, it is important to look at the whole thing from different levels in order to improve a basic understanding and to exchange ideas with internal and external stakeholders. 

There are different categories/levels of how we can obtain AI services: 
 
| Category                | Example                    | Customer influence on the model |
|-------------------------|----------------------------|---------------------------------|
| Application             | Microsoft Teams Premium    | Low to none                     |
| Application Platform    | Power Virtual Agent         | Limited influence               |
| Scenario-based services | Azure Cognitive Search      | Limited influence               |
| Custom AI models        | Azure Open AI, ChatGPT, Dell-E | Stronger influence           |
| ML Platform             | Azure Machine Learning platforms | Complete Impact             |
 
An example of the application layer is Microsoft Teams Premium, which uses AI services to automatically generate tasks from a Teams meeting based on the video and voice stream. However, the generated content cannot be adapted to customer-specific content, such as internal abbreviations of departments or products. In other words, the customer has no influence on the model. Use cases are diverse and helpful, but limited to the intended functions of the application and the manufacturer. These can be very powerful applications. If you take a look at M365 Copilot, you already have a very impressive application here.
 
If we look at the application platform, we can influence the models with our data, using Generative AI by the manufacturer. This applies to both inputs and outputs. Cognitive services or even machine learning are also used to improve the model with specific capabilities. For example, Power Virtual Agent can create workflows based on input, or Power App designs can be created from pencil sketches. Customers can also read, classify and process certain data. However, you are still limited to the pre-trained models. 
 
Examples of scenario-based services that include AI include Azure Cognitive Search, Form Recognizer, Metrics Advisors, and so on. These services can be consumed by apps and integrated into various scenarios. Azure Cognitive Search, or soon Vector Search (preview), provides out-of-the-box AI capabilities, such as exact keyword matching, multilingual search, and semantic search, that can be integrated into applications and improve the user experience.
 
Customize AI models currently have a high appeal, as Azure Open AI is part of this category. In addition to Vision, Speech Languages & Decision AI Models, ChatGPT and Dell-E can also be consumed in Azure. These models have been available for a long time and are used to improve our experience, address cost pressures, but also to develop completely new products and new business models. All services are enriched and trained with the help of customer data. However, it is still a pre-trained model from Microsoft. You could say that a separate flavor of a pre-trained model is created here.
 
The ML platform gives you the ability to train your own models based on your own data. You are not dependent on how good a pre-trained model is. Both training data and test data come from customers. Data Preparation, Build and Train, Validate, Deploy and Managed and Monitor are in the hands of customers.

AI services can be combined depending on the use case and technical availability. Therefore, a cost analysis based on a business plan and the requirements for an AI project is recommended.
 
You quickly realize that if you approach the possibilities of AI projects exclusively from the cost side, you may neglect important decision-making criteria . However, an understanding of different cost structures for AI services in Microsoft products is of course useful and helpful. 

The cost of AI services varies depending on the use case and should always be considered in the context of business value. Here is an overview of the cost structures that will give you a first idea of how procurement costs might be composed:

| Category                | Examples                  | Cost                                                                 |
|-------------------------|---------------------------|----------------------------------------------------------------------|
| Application             | Microsoft Teams Premium, Microsoft Copilot                            | Price per user/pre-paid/month                                       
| Platform                | Power Virtual Agent, Power Automate, AI Builder                       | Different pricing models:                                            
                                                                                                     - Per user                |
                                                                                                     - Per Services Credits    |
                                                                                                     - Pre-Paid / Month        |
                                                                                                     - Depending on units (text characters, images, pages) |
| Scenario-based          | Azure Cognitive Services, Form Recognizer, etc.                       | Usage-based costs, pay-as-you-go, commitment tier      |
| Azure Cognitive Search  | Azure Cognitive Search                                               | Cost depends on tier model, units in time, memory type  |
| Applied AI / Cognitive Services | Open AI Models                                                    | Per token, depending on model type and number of tokens processed   |
| Azure Machine Learning platforms | Azure Machine Learning platforms                                 | Depending on time unit, compute resources, tokens, chats commitments |

An important aspect that buyers and technicians should consider is the influence of commitments on costs. In many cases, longer commitments to AI services offer cost advantages in terms of time and computing power. These commitments can prove to be a smart investment to reduce costs and stay in control of spending in the long run.

Inference:
Choosing the right AI services for your business requires a thorough understanding of cost structures. It's important to consider not only the immediate costs, but also the business benefits and long-term impacts. Each level of AI services offers specific cost models that can be customized to fit the use case and business needs. Through careful planning, consideration of commitments, and alignment with business goals, buyers and technicians can ensure that the implementation of AI services is both economically and strategically beneficial.
 
 
It is also important to think about scalability and usage volume in order to keep costs under control in the long term. A lot doesn't always have to cost more. All services are scalable in the cloud. Even though every service certainly has technical limitations, there are always opportunities to expand them further. However, it is advisable to look at when which resources are needed, what usage behavior is present and whether there are load peaks. When working with ML models, you should take a cost-use view of resources, monitor utilization and take into account the temporary provision of resources from the outset in order to avoid unnecessary cost drivers right from the start. A DevOps strategy can unleash high optimization potential here.
 
Again and again, this topic of cost control seems to receive too little attention. We negotiate a contract once a year, then we meet again after 3 years and everyone is unhappy. In my opinion, companies and partners should strive to always allocate costs according to causation. This not only saves costs, but also provides clear arguments as to why a service is used or should no longer be used. Of course, it is not always possible, since resources are always used by more than one polluter, but all activities should be aimed at moving from a pure cost analysis of IT services to a revenue analysis. Here, sensible concepts should be considered to ensure the control of AI projects.

AI projects always have project costs. Even though an AI is introduced as an add-on at the application level and there are no development costs, the adoption of these new services should not be underestimated. Typically, such projects are planned in sprints, every 14 days. The sprints can be priced with "T-shirt sizes" and thus offer flexibility within a fixed price per sprint to implement agile ways of working with a certain degree of cost control. Often, this is not a make-or-buy consideration, but rather a strategic decision, since neither the customer nor the service provider can cover all topics and should hand over responsibilities. Since the development of the models is progressing rapidly, an agile methodology that aims for value and involves collaboration with partners is recommended. 100% outsourcing is not advantageous in most cases, as the process know-how and responsibility for the data should remain with the customer and cannot be delegated.
 
Let's move on to one of the more complex cost blocks: support and managing service costs. Probably one of the most important issues when it comes to long-term cost drivers. While technical support on traditional IT services and developed applications is still relatively easy to price and compare, support and managing services costs in the ML space can potentially be more complex due to their requirements. Obvious topics should be summarized from an application point of view, and the partner should look at services consolidated per topic and expertise (from a single source), even if basic services may be required.
 f ces are available at a lower cost elsewhere. In the long run, the costs are higher when a service is divided among too many individual responsibilities. Within an AI project, even in the prototype phase, the idea of support and service should always be considered, also from a cost point of view. A service cost corridor should be defined and added value should be questioned in order to avoid high costs in the event of poor service.

Infrastructure costs can only really be determined once the scope is known. Depending on the scope and once the infrastructure costs have been determined, it is always worthwhile to think again about the total cost of ownership costs, especially in the area of services. It could make sense to purchase individual services directly from the manufacturer in order to optimize service costs and the overall experience over the term – and vice versa. If you have planning security for the consumption of infrastructure, this could result in cost advantages.
Terms and Terms. 

All services can be obtained via Microsoft's common contract models. As a first step, it is recommended that you familiarize yourself with the services free of charge. You can easily create this in the Azure portal. It requires approval from Microsoft before it can be used with OpenAI. The corresponding link can be found in the Azure portal when creating the OpenAI Services. Here you should also have the Terms & Conditions evaluated before you take the first step into an AI journey.

Costs in terms of integration and compatibility should not be underestimated and turn out to be a cost driver in the long term. Often, companies are not yet ready to use AI models efficiently, to train them, because data is simply not as available as it is needed. It is often worthwhile to deal intensively with this when evaluating a project so that you are not surprised later by follow-up projects, infrastructure and service costs.

We see that AI projects should not be considered exclusively on the cost side. It is important to create basic structures for a total cost of value analysis. Because apart from being a cool technology, there are numerous business cases that show that implementing AI makes sense in almost all areas.
There is often concern that AI will destroy jobs. But in reality, there is often no other choice, as certain tasks simply cannot be done effectively by humans. Either the resources are not available or the human labor is not enough to solve the problem.
Let's look at a specific case: the implementation of a voice assistant (bot) in a small contact center in Germany. There are currently five agents working there and an average of 60 calls are received per day. Most calls are between 9 a.m. and 10 a.m. So tomorrow a lot of calls can be answered and in the afternoon there are a lot of apprenticeship times. The goal is to improve agent efficiency and utilization, reduce call wait times, and optimize customer service. This is to be achieved by routing calls to the most appropriate agent based on the topic and providing automated support in specific scenarios.

Three use cases with a voicebot can achieve this:

A voicebot can make better and more user-friendly routing decisions than any traditional interactive voice response (IVR) today. Customers who cannot be served during peak hours receive appointment suggestions for callback times, which the user can easily select. In addition, the bot itself can answer 25% of the requests.

There are numerous advantages to implementing a voicebot. But how can you calculate the return on investment (ROI) over a three-year period? By comparing the expected cost savings from reducing wait times and improving agent efficiency with the cost of implementing and maintaining the voicebot. You'll quickly realize that the adoption of AI services benefits everyone involved.
 
Overall, it can be seen that the introduction of AI in your company brings far-reaching benefits. From improving customer service to increasing efficiency to reducing wait times, AI can help you achieve your business goals. Take the time to analyze the different use cases and calculate the ROI. You'll find that implementing AI services is an investment that pays off in the long run. Or to put it in the words of one of my customers – The Business Case are Nuts. 

#### Four primary ways to use Generative AI ####
### Create ###
Using generative AI to create new content, such as: 

Writing articles, emails, and social media posts.
- Generate text responses to customer service inquiries using Conversational AI. 
- Draft emails to clients using Gemini in Gmail.

Creating images, videos, and audio
- Create a custom image for a presentation using Gemini in Google Slides.
- Generate multiple design concepts for brainstorming marketing materials such as website pages using Imagen.
- Create video tutorials to guide customers through troubleshooting steps using Google Vids.

Generating code in various programming languages
- Generate unit tests and other test cases for code, reducing the manual effort required for testing while still ensuring the code works as expected.
- Generate code as a starting point for larger software development projects using Gemini Code Assist.

### Summarize ###
Condense large amounts of information into concise summaries, such as:

Summarizing long documents or articles
- Summarize a lengthy financial report without having to read the entire document using NotebookLM Enterprise.
- Summarize customer reviews to understand product feedback and sentiment using Gemini in Looker.

Extracting key takeaways from meetings or presentations
- Project managers can automatically generate meeting notes that highlight key decisions and action items using Gemini in Google Meet.
- Sales teams can use summaries to quickly recap client calls and identify next steps.

Creating concise reports from complex data
- Transform complex data into easily understandable visuals like graphs using Gemini in BigQuery.

### Discover ###
Help your customers and employees find what they need at the right time, such as:

Uncovering hidden patterns and insights in data
- Analyze purchase history and website traffic to predict future demand and optimize inventory using forecasting models on Vertex AI.
- Identify viewing patterns of streaming viewers to recommend personalized content to subscribers, increasing engagement and reducing churn using Vertex AI Search.
- Analyze vast datasets of molecular structures to identify potential drug candidates with higher success rates by fine-tuning models on Vertex AI.

Searching for resources or documents 
- Search for a file or ask questions about its contents using Gemini in Google Drive.
- Unlock enterprise expertise for employees with agents that bring together Gemini’s advanced reasoning, Google-quality search, and enterprise data, regardless of where it’s hosted using Google Agentspace.

Monitoring real-time events
- Use anomaly detection to identify fraudulent transactions and prevent financial losses.

### Automate ### 
Automate tasks that previously required human intervention, such as:

Automated format conversation
- Convert content to accessible formats in real time by using Google Cloud's APIs, like Text-to-Speech, Speech-to-Text, Translation, and more.

Automated documentation
- Analyze code and automatically generate clear and concise documentation, saving developers time and ensuring consistency using Codey. 
- Automate contract review and information extraction with Document AI.

Automated notifications and alarms
- Automate customer feedback analysis and ticket creation.


Multimodal GenAI - Gen AI can process and integrate information from diverse formats like plain text, images, videos, audio, and PDFs. This capability–known as multimodal gen AI–means that models can process various input types individually or combine multiple kinds of data simultaneously.

Vertex AI is Google Cloud's unified machine learning (ML) platform. It empowers you to build, train, and deploy ML models and AI applications. For multiple modalities (text, code, images, speech), Vertex AI gives you access to Google's large generative AI models through Model Garden. You can tune Google's LLMs to meet your needs, and then deploy them for use in your AI-powered applications.

### Reinforcement learning ###

Reinforcement learning is all about learning through interaction and feedback. Imagine a robot learning to navigate a maze. It starts with no knowledge of the maze's layout. As it explores and interacts with the maze, it collects data—bumping into walls (negative feedback) or finding shortcuts (positive feedback). Through this process of trial and error, the algorithm learns which actions lead to the best outcomes. It's like training a pet. You reward good behavior and discourage bad behavior. And over time, the pet learns to perform the desired actions. Similarly, in reinforcement learning, the algorithm learns to maximize rewards and minimize penalties by interacting with its environment. This type of learning is particularly useful in situations where you can't provide explicit instructions or labeled data. For example, you could use reinforcement learning to train a self-driving car to navigate complex traffic situations or to optimize the performance of a robot in a manufacturing plant.

### Examples of machine learning approaches on Google Cloud ####

1. Predictive maintenance with Vertex AI (supervised learning) - By training a model on sensor data from machines like temperature, pressure, and vibration, Vertex AI can predict when a machine is likely to fail, enabling proactive maintenance and reducing downtime.

2. Anomaly detection with BigQuery ML (unsupervised learning) - BigQuery ML can analyze historical transaction data (amount, location, time, etc.) to identify patterns and flag unusual transactions that deviate significantly from the norm. This helps prevent fraud and minimize financial losses.

3. Product recommendations with Vertex AI (reinforcement learning) - Vertex AI can train a reinforcement learning model to recommend products to users based on their browsing history, purchase behavior, and other factors. The model learns to maximize user engagement and sales by continuously refining its recommendations.

### Data tools and management for ML workloads ###

Google Cloud offers a comprehensive suite of data tools and management capabilities tailored for ML workloads. These tools and capabilities are designed to support the entire ML lifecycle, from data preparation and model training to deployment and monitoring. 

1. Gather the data - Data gathering, also called data ingestion, involves collecting raw data from various sources. To effectively train and test your model, determine the data you need based on the outcome you want to achieve. Google Cloud supports data ingestion through several tools. 
- Pub/Sub handles real-time streaming data processing, regardless of the structure of the data.
- Cloud Storage is well-suited for storing unstructured data.
- Cloud SQL and Cloud Spanner are used to manage structured data.

2. Prepare your data - Data preparation is the process of cleaning and transforming raw data into a usable format for analysis or model training. This involves formatting and labeling data properly. Google Cloud offers tools like BigQuery for data analysis and Data Catalog for data governance. These tools help prepare data for ML models. 
- With BigQuery, you can filter data, correct its inconsistencies, and handle missing values. 
- With Data Catalog, you can find relevant data for your ML projects. This tool provides a centralized repository to easily discover datasets in your organization.

3. Train your model - The process of creating your ML model using data is called model training. Google Cloud's Vertex AI platform provides a managed environment for training ML models. 
With Vertex AI, you can set parameters and build your model, using prebuilt containers for popular machine learning frameworks, custom training jobs, and tools for model evaluation. Vertex AI also provides access to powerful computing resources to make the model training process faster.

4. Deploy and predict - Model deployment is the process of making a trained model available for use. 
Vertex AI simplifies this by providing tools to put the model into action for generating predictions. This includes scaling the deployment, which means adjusting the resources allocated to the model to handle varying amounts of usage.

5. Manage your model - Model management is the process of managing and maintaining your models over time. Google Cloud offers tools for managing the entire lifecycle of ML models. This includes the following.
- Versioning: Keep track of different versions of the model.
- Performance tracking: Review the model metrics to check the model's performance.
- Drift monitoring: Watch for changes in the model's accuracy over time.
- Data management: Use Vertex AI Feature Store to manage the data features the model uses.
- Storage: Use Vertex AI Model Garden to store and organize the models in one place.
- Automate: Use Vertex AI Pipelines to automate your machine learning tasks.

All these Google Cloud tools are designed to work together seamlessly. You can also connect them with your existing tools or build your own custom solutions. And throughout the entire process, Google Cloud's infrastructure ensures your solution is available and reliable. At the same time, Identity and Access Management (IAM) keeps your data safe and ensures only the right people have access.

#### Deep learning ####

A broad field that encompasses many different techniques, one of which is deep learning (DL). Deep learning is a powerful subset of machine learning, distinguished by its use of artificial neural networks. These networks enable the processing of highly complex patterns and the generation of sophisticated predictions. Neural networks can leverage both labeled and unlabeled data, a strategy known as semi-supervised learning. They train on a blend of a small amount of labeled data and a large amount of unlabeled data. That way, they learn foundational concepts and generalize effectively to novel examples. Generative AI uses the power of deep learning to create new content spanning text, images, audio, and beyond. Deep learning techniques, particularly those centered on neural networks, are the engine behind these generative models.

Remember foundation models from course one? Foundation models use deep learning. They are trained on massive datasets that allow them to learn complex patterns and perform a variety of tasks across different domains. They are incredibly powerful machine learning models trained on a massive scale, often using vast amounts of unlabeled data. This training allows them to develop a broad understanding of the world, capturing intricate patterns and relationships within the data they consume. Think of a foundation model as a highly advanced learner. It's like a student who has read everything in an entire library, absorbing knowledge from countless books, articles, and websites. This deep and extensive learning allows foundation models to be adapted to a wide range of tasks.

Large Language Models (LLMs) - One particularly exciting type of foundation model is the LLM. These models are specifically designed to understand and generate human language. They can translate languages, write different kinds of creative content, and answer your questions in an informative way, even if they are open ended, challenging, or strange. This is likely the most common foundation model you've encountered, such as in popular generative AI chatbots like Gemini. They also help power many search engines you use today. 

Diffusion models - Diffusion models are another type of foundational model. They excel in generating high-quality images, audio, and even video by iteratively refining noise (or unstructured/random data and patterns) into structured data.


### Factors when choosing a model for your use case ###

1. Modality - When selecting a generative AI model, it's crucial to consider the modality of your input and output. Modality refers to the type of data the model can process and generate, such as text, images, video, or audio. If your application focuses on a single data type, like generating text-based articles or creating audio files, you'll want to choose a model optimized for that specific modality. For applications that require handling multiple data types, such as generating image captions (processing images and producing text) or creating video with accompanying audio, you'll need a multimodal model. These models can understand and synthesize information across different modalities.

2. Context window - The context window refers to the amount of information a model can consider at one time when generating a response. A larger context window allows the model to "remember" more of the conversation or document, leading to more coherent and relevant outputs, especially for longer texts or complex tasks. However, larger context windows often come with increased computational costs. You need to balance the need for context with the practical limitations of your resources.

3. Security - Security is paramount, especially when dealing with sensitive data. Consider the model's security features, including data encryption, access controls, and vulnerability management. Ensure the model complies with relevant security standards and regulations for your industry.

4. Availability and reliability - The availability and reliability of the model are crucial for production applications. Choose a model that is consistently available and performs reliably under load. Consider factors like uptime guarantees, redundancy, and disaster recovery mechanisms.

5. Cost - Generative AI models can vary significantly in cost. Consider the pricing model, which might be based on usage, compute time, or other factors. Evaluate the cost-effectiveness of the model in relation to your budget and the expected value of your application. This is where selecting the right model for the right task is important. Be sure to match the model to the task; bigger isn't always better, and multi-modal capabilities aren't always necessary.

6. Performance - The performance of the model, including its accuracy, speed, and efficiency, is a critical factor. Evaluate the model's performance on relevant benchmarks and datasets. Consider the trade-offs between performance and cost.

7. Fine-tuning and customization - Some models can be fine-tuned or customized for specific tasks or domains. If you have a specialized use case, consider models that offer fine-tuning capabilities. This often involves training the model further on a specific dataset related to your use case.

8. Ease of integration - The ease of integrating the model into your existing systems and workflows is an important consideration. Look for models that offer well-documented APIs and SDKs.

### Google Cloud's ML models ###

Vertex AI streamlines the integration of advanced artificial intelligence capabilities into business applications, allowing for seamless discovery, deployment, and customization. These models empower businesses to leverage cutting-edge AI, providing the flexibility to work with many different models without the need for extensive in-house model development. 
With Vertex AI you can access models developed by Google including Gemini, Gemma, Imagen, and Veo. You can also access proprietary third-party models, and openly available models.

Gemini - Gemini, a multimodal model, can understand and operate across diverse data formats, such as text, images, audio, and video. Gemini's multimodal design supports applications that require complex multimodal understanding, advanced conversational AI, content creation, and nuanced question answering.

Gemma - A family of lightweight, open models is built upon the research and technology behind Gemini. They offer developers a user-friendly and customizable solution for local deployments and specialized AI applications.

Imagen - A powerful text-to-image diffusion model, it excels at generating high-quality images from textual descriptions. This makes it invaluable for creative design, ecommerce visualization, and content creation.

Veo - A model capable of generating video content. It can produce videos based on textual descriptions or still images. Its functionality allows for the creation of moving images for applications such as film production, advertising, and online content.

Collectively, these Google Cloud foundation models empower businesses to enhance customer experiences through intelligent chatbots and personalized content. They increase productivity by automating tasks and improving information retrieval. They foster innovation by generating new ideas and designs. They also derive data-driven insights for improved decision-making.


### Google strategies for foundation model limitations ###


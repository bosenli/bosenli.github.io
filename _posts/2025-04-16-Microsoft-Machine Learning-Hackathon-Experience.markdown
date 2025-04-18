<!-- ---
layout: post
title: "Microsoft Hackathon on ML 2 days"
date: 2025-04-16
categories: [Tech, ML,Security]
tags: [cybersecurity, ML]
show_date: true
show_date_relative: false
--- -->



<!-- ---
layout: post
title:  "Welcome to Jekyll!"
date:   2025-04-16 12:56:17 -0400
categories: jekyll update
--- -->
This is my first time joining hackathon, the work pace was super intensive. Love the collaborative work. It inspired me to join more and keep learn more to make up my knowledge weakness.
<div style="text-align: center;">
  <img src="{{ site.baseurl }}/assets/images/hackathonmicrosoftteam4172025.png" alt="Hackathon Team" style="max-width: 100%; height: auto;" />
  <p><strong>Team Up with GM senior leaders</strong></p>
</div>

Problem Scenario trying to solve:

Woodgrove Retail with declining sales. Apply Azure AI to analyze and provide business solutioning. 
Inventory Optimization:
Implement an AI-driven system that predicts inventory needs based on historical data, seasonal trends, and real-time sales. Use Azure OpenAI for predictive modeling and Azure AI Search to provide fast, relevant search results for inventory queries.

Customer Engagement:
Develop a personalized customer engagement system that uses Azure Vision to recognize products in customer-uploaded images and Azure Speech to facilitate voice-based queries and support.

Create a chatbot using Azure OpenAI and integrate Semantic Kernel to enable more sophisticated and context-aware interactions with customers. Semantic Kernel will help in understanding and processing customer inputs, generating relevant responses, and maintaining conversation context.

Deployment and Scalability:
Host the enhanced application using Azure App Service for easy deployment and scaling.
Use PromptFlow to manage the different AI models used in the platform, ensuring they are properly integrated and optimized for performance.

Data Management:
Store and manage inventory using Azure SQL Database for relational data.
Store current article images and customer images in Azure Blob Storage.

Expected Solution:
Each team will deliver a fully functional prototype of the Smart Inventory Management and Customer Engagement Platform. The prototype should demonstrate:

Effective Use of AI: The platform should show how AI can predict inventory needs and engage customers.

Seamless Integration: The solution should integrate multiple Azure services and databases to form a cohesive system, with a focus on utilizing Semantic Kernel for advanced natural language understanding and interaction.

Scalability: The application should be designed with scalability in mind, using Azure’s cloud capabilities.

Usability: The platform should enhance the user experience for both the retail company’s staff (inventory management) and customers (engagement).

Challenge 0 – Development Environment Configuration:
Ensure that you have the required prerequisites before diving into the challenges. The required software is already pre-installed in your hackathon environment: Visual Studio Code, SQL Server Management Studio (SSMS), Pandoc v3.5, Python v3.10.11, Node.js v18.16.1, and .NET Core v8.0.

Challenge 1 – Query SQL Server Data:
Participants need to restore an SQL Server backup and query the data using SQL Server Management Studio in Azure. The objective is to analyze the data through views or custom queries, uncover insights, and solve business challenges faced by the company.

Challenge 2 – Use Machine Learning to Expose Data Issues:
This challenge requires participants to set up an Azure Machine Learning compute environment, create datasets, and build a pipeline to transform the data. After running the pipeline, participants will train a machine learning model, deploy it as a service, and test it to detect data issues.

Challenge 3 – Search Based on Images:
The goal is to use Azure Custom Vision to build a model that identifies and matches user-uploaded images with similar products. Upload and tag images, train the model, and use the Quick Test feature to validate its accuracy in recognizing product categories.

Challenge 4 – RAG Pattern:
Participants will use the Retrieval-Augmented Generation (RAG) pattern to process data from SQL Server and images. They will generate PDFs from this data and upload them to Azure Blob Storage. Using Azure Cognitive Services, they will extract and enhance data from the PDFs, including article numbers, categories, and related images.

Challenge 5 – Advanced Retrieval Augmented Generation (RAG) Pattern

Background Story:
So far, many of the technologies and techniques provide value but none are really providing deep analytics and search results that provide the power to make decisions quickly.

Technical Details
Integrate components:

ML predictions

Visual search

Cognitive search

Azure OpenAI

Challenge 6 – Add AI Application to App:
In this challenge, participants will create an Azure AI Search index based on the SQL database view, implement an API for natural language queries of the Azure AI Search index to get a chat application running locally using Python environment.



<!-- You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. You can rebuild the site in many different ways, but the most common way is to run `jekyll serve`, which launches a web server and auto-regenerates your site when a file is updated.

Jekyll requires blog post files to be named according to the following format:

`YEAR-MONTH-DAY-title.MARKUP`

Where `YEAR` is a four-digit number, `MONTH` and `DAY` are both two-digit numbers, and `MARKUP` is the file extension representing the format used in the file. After that, include the necessary front matter. Take a look at the source for this post to get an idea about how it works.

Jekyll also offers powerful support for code snippets:

{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/ -->

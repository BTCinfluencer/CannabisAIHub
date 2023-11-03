# CannabisAIHub
Building AI course project "Cannabis AI Hub"
<!-- This is the markdown template for the final project of the Building AI course, 
created by Reaktor Innovations and University of Helsinki. 
Copy the template, paste it to your GitHub README and edit! -->

Cannabis AI Hub

Final project for the Building AI course

## Summary

"Cannabis AI Hub" would be suitable for a project that gathers information, resources, and artificial intelligence applications related to cannabis 
"Cannabis AI Hub" will feature a cannabis product recommendation platform, an information center, educational and dosing tools, cannabis strain data analysis, and a community forum.



## Background

Lack of reliable information: Many people struggle to find reliable information about cannabis strains, their effects, medical applications, and the laws surrounding them. CannabisAIHub can serve as a trusted source of information.
Customization of cannabis choices: AI can personalize product recommendations based on individual preferences and needs, helping people make more informed choices.
Dose management: An AI tool can educate users on proper dosages to prevent overconsumption.
Access to data: The cannabis industry is constantly evolving, but accessing the latest data and research can be challenging. CannabisAIHub can centralize information and make it accessible to everyone.
Compliance with regulations: Cannabis laws and regulations vary from one region or country to another. AI can help inform users about the legality of their geographical situation.

The personal motivation behind this project could stem from an interest in education, technology, and enhancing safety and responsibility in cannabis use. This topic is of great significance as it intersects issues of public health, cannabis legalization, and technology. It provides an opportunity to assist individuals in making more informed decisions regarding cannabis, promoting responsibility and safety, and contributing to the advancement of the cannabis industry towards higher standards of information and transparency.

## How is it used?

"The "Cannabis AI Hub" project aims to provide information, recommendations, and tools to help users make informed decisions regarding cannabis.

Usage Process:
Platform Access: Users access the "Cannabis AI Hub" platform by visiting the website.
Needs Identification: Users are prompted to define their needs and preferences, whether for recreational or medical use, pain management, insomnia, anxiety, etc.
Personalized Recommendations: AI analyzes user data and offers recommendations for cannabis-based products, including cannabis strains, oils, edibles, or other forms of consumption.
Education and Information: Users can access educational resources about cannabis, including guides, articles, and information on current legislation in their region.
Simulations: If a user wishes to understand the potential effects of different cannabis doses, they can use AI tools to simulate these effects.
Community Forum: Users can participate in discussions about cannabis, share their experiences, and ask questions.

Types of Situations and Users:
Novice Cannabis Users: Novices looking to learn more about cannabis and make informed decisions about its use.
Medical Patients: Patients seeking to use cannabis for medical purposes, such as chronic pain relief, anxiety, or other conditions.
Recreational Users: Recreational consumers looking to explore new cannabis strains or understand appropriate dosages to avoid unwanted effects.
Healthcare Professionals: Doctors and healthcare professionals in need of up-to-date information on medical cannabis.
Experienced Consumers: Seasoned consumers wanting access to advanced information on cannabis strains and community resources.


Image - test1

![Cat](https://github.com/BTCinfluencer/CannabisAIHub/blob/main/CannabisAIHub-003.jpg)
<img src="https://github.com/BTCinfluencer/CannabisAIHub/blob/main/CannabisAIHub-002.jpg" width="300">

# This is how you create code examples:

1 Example of product recommendation using collaborative filtering:

     import numpy as np
# Sample user preferences and product data
user_preferences = np.array([4.0, 3.5, 0.0, 4.5, 0.0])  # User's ratings for different product features
product_data = np.array([
    [4.5, 4.0, 4.2, 0.0, 4.0],  # Product 1 feature ratings
    [3.8, 4.2, 3.5, 4.0, 0.0],  # Product 2 feature ratings
    [0.0, 4.4, 4.0, 0.0, 4.3],  # Product 3 feature ratings
    [4.0, 0.0, 3.8, 4.5, 3.9],  # Product 4 feature ratings
])

# Calculate recommendations using collaborative filtering
def recommend_product(user_preferences, product_data):
    scores = np.dot(user_preferences, product_data.T)
    recommended_product = np.argmax(scores)
    return recommended_product

recommended_product = recommend_product(user_preferences, product_data)
print(f"Recommended product: Product {recommended_product + 1}")

    
2. Example of simulating cannabis effects:
# Create a function to simulate cannabis effects based on dose and strain
def simulate_effects(dose, strain):
    # Add your code for simulating effects here
    simulated_effects = f"Simulated effects for {dose}g of {strain} strain."
    return simulated_effects

# Example usage
simulated_effects = simulate_effects(3, "Indica")
print(simulated_effects)


    
3. Example of data retrieval using Requests:
import requests

# Define the URL of the data source
url = "URL_of_data_source"

# Send a GET request to retrieve data
response = requests.get(url)

# Check if the request was successful
if response.status_code == 200:
    data = response.text
    # Analyze the retrieved data here
    print(data)
else:
    print(f"Failed to retrieve data. Status code: {response.status_code}")



## Data sources and AI methods

Data Sources:
Public Databases: Gather data from government databases, cannabis research centers, regulatory reports, and other public sources.
Cannabis Websites: Many websites dedicated to cannabis provide information on strains, products, effects, etc. Consider collaborating with these sources or scraping them to collect data.
Testing Laboratories: Cannabis testing labs provide data on the chemical composition of strains. Obtain this data through partnerships or agreements.
Forums and Communities: Discussion forums and online communities can provide information on user experiences. Consider extracting anonymized information from these sources.

Methods of AI:
Supervised Learning: Train machine learning models using labeled data to create product or effects recommendation systems.
Unsupervised Learning: Unsupervised learning methods can be used for data analysis and categorization of cannabis strains.
Natural Language Processing (NLP): If considering the analysis of forums or communities, NLP can help extract useful information from unstructured text.
Simulation: AI can be used to simulate the effects of different doses and strains of cannabis based on chemical data and known effects.
Data Fusion: Integrate data from various sources using data fusion methods to provide users with more comprehensive information.


Government Databases:

Search the websites of government authorities responsible for cannabis regulation in your region.
Specialized Cannabis Websites:
Explore specialized cannabis websites such as Leafly, High Times, or Weedmaps, which provide information on strains, products, effects, and reviews.
Testing Laboratories:
Contact cannabis testing laboratories like Steep Hill and inquire whether they are willing to share data on the chemical composition of cannabis strains.
Online Forums and Communities:
Explore discussion forums and online communities related to cannabis, such as Grasscity or Reddit's r/trees. These sources can provide information on user preferences and experiences.
Research Resources:
Search for scientific research articles in databases like PubMed, which may contain information on the medical aspects of cannabis.
Local Government Sources:
If cannabis is legalized in your region, check your local government's website for information on specific laws and regulations in your area.



Where does your data come from? Do you collect it yourself or do you use data collected by someone else?
If you need to use links, here's an example:
[Twitter API](https://developer.twitter.com/en/docs)

| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title       |
| Paragraph   | Text        |

## Challenges


What the project does not address:
Individual Health Issues: The project can provide general information about cannabis but cannot diagnose or treat specific health problems. Users with health issues should consult a healthcare professional.
Variability of Effects: The effects of cannabis can vary significantly from one person to another based on individual factors. The project can offer general recommendations, but it cannot accurately predict how a specific individual will react.
Dependence and Abuse: The project should be used with caution to avoid promoting cannabis abuse. It should include information about the risks of dependence and abuse.
Legal Issues: Cannabis laws and regulations vary from one region to another. The project can inform users about general legislation, but it cannot provide specific legal advice for each situation.

Ethical Considerations:
Privacy Protection: Data collection regarding cannabis preferences and use should be conducted in a way that safeguards users' privacy. It's important to obtain informed consent and securely store the data.
Balanced Content and Recommendations: The project should provide objective and balanced information about cannabis, avoiding the promotion of excessive or irresponsible consumption.
Transparency: Methods for product recommendations and effects simulation should be transparent so that users understand how suggestions are generated.
Equal Access: The project should be accessible to all, avoiding discrimination and ensuring that information is understandable for a broad audience.
Ongoing Education: It's important to provide regularly updated educational resources to reflect the latest research and regulations related to cannabis.

## What next?

The "Cannabis AI Hub" project has the potential to grow and become an even more valuable resource in the future. Here are some ways it could evolve and expand:

Feature Expansion: You could broaden the platform's capabilities by adding new AI tools, such as more advanced simulators, real-time dosing tools, or chatbots for instant responses.
Internationalization: You could extend the project to support different languages and regions, providing location-specific information.
Partnerships: Collaborate with cannabis testing labs, industry businesses, health experts, and government organizations to access high-quality data and resources.
Mobile Applications: Develop mobile apps to make the project more accessible to users on their smartphones and tablets.
Training and Awareness: Organize workshops, webinars, and training programs to educate the public, healthcare professionals, and cannabis dispensaries on best practices.
Advanced Artificial Intelligence: Explore advanced AI domains, such as deep learning, to enhance the accuracy of recommendations and simulations.

To advance this project, you will need various skills, including:

Web and Mobile App Development: To expand features and provide a high-quality user experience.
Artificial Intelligence Expertise: To enhance AI models, develop new tools, and ensure accurate recommendations.
Domain Knowledge: A deep understanding of the medical, legal, and cultural aspects of cannabis is essential.
Privacy Protection and Data Security: To ensure the confidentiality and security of user data.
Education and Awareness: To inform the public and healthcare professionals about the benefits and risks of cannabis.


## Acknowledgments

* list here the sources of inspiration 
* do not use code, images, data etc. from others without permission
* when you have permission to use other people's materials, always mention the original creator and the open source / Creative Commons licence they've used
* etc

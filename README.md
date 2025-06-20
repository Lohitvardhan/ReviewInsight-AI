# Quality Assessment

Designed a system to analyze and evaluate product quality based on customer reviews and social media content, leveraging state-of-the-art natural language processing techniques to assist users in making informed purchasing decisions.

### Customer Feedback Categorization

Initial approaches using CNNs and LSTMs were explored but did not deliver satisfactory performance for sentiment classification. This led to a transition toward Transformer-based architectures, which significantly improved the model's effectiveness. Leveraging state-of-the-art Transformer models, we developed a robust system capable of classifying tweets into positive, neutral, and negative categories with high accuracy. 


### Additional Features

In addition to sentiment classification, the project includes several insightful features to enhance understanding of customer feedback:

- **Word Cloud**: Highlights the most frequently mentioned keywords, giving a quick overview of what users emphasize the most.
- **Sentiment Distribution Pie Chart**: Visualizes the overall sentiment (positive, neutral, negative) across all collected reviews.
- **Multilingual Tweet Translation**: Automatically translates tweets from various languages into English for consistent analysis.
- **User Distribution Map**: Displays the geographical spread of users discussing the product.
- **Top Twitter Platforms Statistics**: Provides insights into the most commonly used platforms for tweeting about the product.

 
### Installation
To run the flask app in a  windows environment

 1. Install python 3.8
 2. Run ```pip install virtualenv```
 3. Run ```mkdir project``` to create project directory
 4. Run ```cd project``` to move to the project directory
 5. Run ```virtualenv venv``` to create a virtual environment
 6. Run ```.\Scripts\activate```  to activate the virtual environment
 7. Install the required dependencies
 8. Copy the contents of the Flask app folder to your virtual environment and use command ```python app.py``` to run the app.  



***

# Fake news detector - CS4824-Final-Project
In the course of this machine learning project, we examined and implemented three different models to solve the challenge of fake news detection. These models included Decision Trees, Multinomial Naive Bayes, and Convolutional Neural Networks (CNNs). Each of these models brought its own unique approach to the problem and enhanced our understanding of machine learning techniques.

Decision Tree
Starting with Decision Tree classifiers, we took a plunge into an intuitive, rule-based approach for decision-making. The concept behind Decision Trees is similar to how we as humans make decisions daily. We create rules and based on these rules, we make decisions. This project helped me understand that similar logic could be applied in machine learning for classification tasks.

However, we found that our decision tree model was computationally heavy, particularly when handling large datasets with a large number of attributes. This led to poor results in terms of accuracy, precision, recall, and F-score. This served as a great lesson in the trade-offs in machine learning - while decision trees are easy to interpret and implement, they can struggle with large, complex datasets and are prone to overfitting.

Multinomial Naive Bayes
Next, we explored the Multinomial Naive Bayes classifier. The underlying Bayes' theorem was a good lesson in understanding the relationship between the likelihood and probability of certain events. In the context of our project, it was exciting to see how we could predict the authenticity of a news story based on its linguistic characteristics.

Unlike the Decision Tree model, our Naive Bayes model performed well in detecting fake news, achieving high accuracy, precision, recall, and F-score. The simplicity of the model, coupled with its high performance, made it a great tool for our task. Yet, it wasn't perfect - the assumption that all classes are independent isn't always true, which is something we learned to consider when choosing a model.

Convolutional Neural Networks (CNNs)
Finally, we implemented a Convolutional Neural Network (CNN). Despite being more complex and computationally intensive than the other two models, the CNN provided us with an entirely different approach to the problem. Instead of treating the text as a set of independent words or phrases, the CNN allowed us to analyze the news articles as integrated wholes, preserving their structure and relationships between words.

The CNN performed well on our task, further proving its power in handling a wide range of machine learning problems. Yet, like the Decision Tree, it required more computational resources and time to train.

Comparison
Each model brought something different to the table. Decision Trees, while simple and intuitive, struggled with the large, complex dataset. The Naive Bayes model performed well and was simple and fast, but its underlying assumptions don't always hold true. The CNN offered an advanced, nuanced approach, but required more computational resources.

Through the process of working with these models, we were reminded that there's no 'one-size-fits-all' in machine learning. Choosing the right model depends on the specific task, the data at hand, and the resources available. The learning we derived from this project was immense, and we look forward to leveraging these insights in our future machine learning endeavours.

# Fashion Recommendation System

This project implements a Retrieval-Augmented Generation (RAG) system for personalized fashion recommendations. The system uses a dataset of fashion items and user input to generate tailored product suggestions.

## Key Features

1. **Data Loading**: Imports a fashion dataset from a CSV file using pandas.

2. **Text Processing**: Utilizes TF-IDF vectorization for processing product descriptions.

3. **Retrieval Function**: Implements a retrieval mechanism that finds relevant products based on user queries using cosine similarity.

4. **User Profile Input**: Collects user information including age, gender, location, and fashion interests through an interactive command-line interface.

5. **Recommendation Generation**: Creates personalized fashion recommendations by combining user profile data with relevant products from the dataset.

6. **Natural Language Output**: Produces human-readable justifications for each recommended product.

## Main Components

- `retrieve_function`: Retrieves relevant products based on a user query.
- `rag_system`: Generates personalized recommendations using the retrieval function and user profile.
- `get_user_profile`: Interactively collects user information.

## Workflow

1. Load the fashion dataset from Kaggle https://www.kaggle.com/datasets/samikshakolhe/pinterest-fashion-dataset
2. Prompt the user for their age, gender, location, and fashion interests.
3. Use this information to query the dataset and retrieve relevant products.
4. Filter and randomly select products that match the user's profile.
5. Generate and display personalized fashion recommendations with explanations.

This system demonstrates a basic implementation of a RAG system for e-commerce recommendations, combining information retrieval techniques with personalized user data to enhance the shopping experience.

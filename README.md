# NLPProductSearchEngine

NLPProductSearchEngine is a Python-based search engine application that leverages various Natural Language Processing (NLP) techniques to help users explore products more efficiently. The application provides functionalities like product search with suggestions, name corrections using edit distance, next-word prediction, and similarity-based product recommendations. This project uses libraries like Pandas, NLTK, Gensim, Spacy, Scikit-learn, and Tkinter to build a user-friendly interface for enhanced product search experiences.

---

## Features

1. **Product Search with Suggestions**:
   - **Input**: User types a query in the search box.
   - **Functionality**: Displays suggestions based on frequent words found in product reviews.
   - **Outcome**: A dropdown list of suggestions matching the user's query.

2. **Product Name Correction**:
   - **Input**: User submits a search query.
   - **Functionality**: Uses **edit distance** to suggest the closest correct product name from available options.
   - **Outcome**: The closest match is suggested and filled into the search box automatically.

3. **Predict Next Word**:
   - **Input**: (Implicit) Based on the corrected or suggested product name.
   - **Functionality**: Predicts the next likely word in the product name using a bigram language model.
   - **Outcome**: Provides an autocomplete feature (not directly shown in this version).

4. **Display Searched Products**:
   - **Input**: User submits a search query.
   - **Functionality**: Searches the product database and displays matching products in a tabular format.
   - **Outcome**: Shows product details (ID, name, brand, category, and rating).

5. **Related Products Based on Similarity**:
   - **Input**: User submits a search query.
   - **Functionality**: Uses **cosine similarity** with word embeddings to find and display products related to the search term.
   - **Outcome**: A list of related products based on similarity.


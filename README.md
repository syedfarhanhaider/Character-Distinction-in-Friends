# Friends Script Character Distinction Project
## Project Overview:
This project focuses on creating a vector representation of character lines in the Friends script data to maximize the distinction between character vectors. The primary goal is to optimize the vector representation to enhance character-based analysis and understanding. The project includes data loading, preprocessing, feature extraction, hyperparameter tuning, information retrieval evaluation, and visualization components.
Project Components:
1. Data Loading and Preprocessing:
•	Files: training.csv, val.csv, test.csv
•	Functions:
•	create_character_document_from_dataframe: Generates character documents from the dataframe.
•	Displaying the number of words for each character in the training set.
2. Preprocessing:
•	Function: pre_process
•	Handles lowercasing, contractions, tokenization, stop word removal, punctuation removal, stemming, number removal, and special character removal.
•	Test the pre_process function on a sample text.
3. Feature Extraction:
•	Functions:
•	to_feature_vector_dictionary: Converts pre-processed tokens and extra features to a feature vector dictionary.
•	Utilizes TF-IDF transformation for feature extraction.
4. Information Retrieval Evaluation:
•	Function: compute_IR_evaluation_scores
•	Computes an IR-based evaluation on training and test data.
•	Evaluates mean rank, mean cosine similarity, and accuracy.
•	Generates a dataframe with similarity measures.
5. Hyperparameter Tuning:
•	Defines parameter grids for preprocessing and feature extraction.
•	Iterates over parameter combinations to find the optimal set of parameters that minimizes the mean rank.
6. Visualization:
•	Functions:
•	plot_heat_map_similarity: Plots a heatmap to visualize the similarity matrix between documents as vectors.
•	Visualizations offer insights into linguistic patterns and relationships among characters.
7. Closest and Farthest Characters:
•	Analyzes and presents the closest and farthest characters based on similarity measures.
Results:
•	Provides a comprehensive analysis of the impact of preprocessing and feature extraction parameters on the mean rank in an IR evaluation.
•	Identifies the optimal set of parameters for maximizing the distinction between character vectors.
•	Visualizations, including heatmaps and character differentiations, offer insights into linguistic patterns and relationships.
Recommendations:
•	The optimized vector representation and identified parameters can be used for character-based analysis in Friends script data.
•	Further exploration can be conducted using advanced natural language processing techniques and deep learning models.
How to Run:
1.	Install necessary libraries using !pip install -r requirements.txt.
2.	Run the project script: python friends_script_analysis.py.
Acknowledgments:
•	The project uses the Friends script data for analysis.
•	Acknowledgment to the creators of NLTK and scikit-learn libraries for their contributions.
Contributors:
•	[Your Name]
•	[Any other contributors]
Feel free to contribute to the project or provide feedback!


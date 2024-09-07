# Extractive-Text-Summarization
This repository consists of the files of my project Extractive Text Summarization model using Restricted Boltzmann Machines (RBM), which utilizes key features like title similarity, sentence position, proper noun score, sentence length, and TF-IDF to generate a feature matrix and sentence matrix. The RBM then enhances this feature matrix, allowing for the selection of the top K sentences to form a concise summary. This project improves efficiency in handling large-scale text, enhancing information retrieval and analysis.

To try this project, download the files in Summariser Folder into a folder in your local system. Install add the dependencies stated in the code and run the streamlit file using "streamlit run streamlit.py" in terminal. You can upload a text file and see the results. 

We have utilized the BBC News Summary Dataset which has nearly 2500 files.

Technologies Used:

Python
Numpy
Pandas
Scikit-learn
NLTK
TensorFlow/PyTorch (for RBM implementation)

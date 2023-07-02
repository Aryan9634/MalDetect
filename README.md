dataset : [CIC](https://www.kaggle.com/datasets/sweety18/cicids2017-wed)

About file arrangement:

The project directory structure is organized into the following subfolders to ensure a well-structured and organized workflow:

1. Inputs: This folder is dedicated to storing the input data required for the project. It contains the datasets, files, or any other relevant data that serves as the input for the analysis and model training.

2. Model: The model folder is designed to hold the trained output models or weights and biases of the neural network. It provides a centralized location to store the trained models that can be utilized for inference or further analysis.

3. Outputs: This folder serves as a repository for storing the output data generated during the project. It includes processed data, visualizations, reports, or any other relevant output generated as part of the analysis or model evaluation.

4. Notebooks: The notebooks folder contains all the notebooks developed during the project. It serves as a comprehensive collection of Jupyter notebooks or any other notebook format used for data preprocessing, model training, evaluation, and visualization. This allows for easy access and reference to the code and analysis performed throughout the project.

5. README: The README file provides a concise overview and serves as a guide for the project. It includes information such as the project's purpose, installation instructions, dependencies, usage guidelines, and any other relevant details for users or collaborators to understand and navigate the project effectively.

By adopting this directory structure, the project ensures a systematic organization of input data, trained models, output data, notebooks, and a comprehensive README file to facilitate collaboration, reproducibility, and efficient project management.

Note: It is recommended to further customize the folder structure based on the specific needs and requirements of the project.





About the project;

Title: Malware Detection using ML Algorithms and Binary Classification

Overview:
This project focuses on malware detection using machine learning algorithms in a binary classification setting. It involves data preprocessing, comparative analysis of classifiers, custom neural network architecture, and model training using PyTorch. The project aims to identify and classify malware based on the available data. Additionally, the future scope of the project includes expanding to multiclass classification and implementing data balancing techniques when computational power permits.

Steps:

1. Data Preprocessing:
   - Utilized pandas and numpy for data preprocessing tasks.
   - Converted the multiclass data into a binary classification format.

2. Comparative Analysis of Classifiers:
   - Implemented batch training on logistic regression, random forest, gradient boosting, and a voting classifier.
   - Conducted a comparative analysis to determine the best-performing classifier.

3. Custom Neural Network Architecture:
   - Developed a custom neural network architecture for malware detection.
   - Trained the network using regular training methods and fit one cycle technique.

4. Model Training using PyTorch:
   - Implemented the project using the PyTorch framework for efficient deep learning tasks.
   - Utilized PyTorch's tools and functionalities for training the custom neural network architecture.

5. Comparative Analysis and Evaluation:
   - Conducted a comparative analysis of different models and techniques used in the project.
   - Evaluated the performance of the models based on their accuracy and other relevant metrics.

Future Scope:
Given sufficient computational power, the project can be expanded in the following ways:

1. Multiclass Classification:
   - Instead of converting the data into binary classification, implement multiclass classification techniques to classify malware into multiple categories. This would allow for more fine-grained classification of different types of malware.

2. Data Balancing:
   - Apply data balancing techniques such as undersampling and oversampling from imblearn to address class imbalance in the multiclass data. This ensures equal representation of each class during training and improves the model's performance.

3. Hyperparameter Optimization:
   - Perform hyperparameter optimization on the neural network and ML models to fine-tune their performance. This process can help identify the best set of hyperparameters for improved accuracy and generalization.

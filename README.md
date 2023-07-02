# Attribute-Prediction

Attribute prediction refers to the process of using machine learning algorithms and techniques to predict the values of specific attributes or features in a dataset based on other available attributes. This approach is commonly used in various domains, including finance, marketing, healthcare, and image recognition.

In the context of Python, attribute prediction typically involves utilizing libraries and frameworks such as scikit-learn, TensorFlow, or PyTorch to build and train predictive models. These models can be trained on labeled datasets, where the attributes to be predicted are already known, to learn patterns and relationships between different attributes. Once trained, the models can be used to make predictions on new, unseen data.

The process of attribute prediction in Python generally involves the following steps:
1. Data Preprocessing:-
   Don't forget to do this ``color_attribute = df[df['tags'].isin(['colours', 'colour', 'colors', 'color'])]`` if you find this kind of tags.
2. Feature Selection/Extraction
3. Model Selection
4. Model Training
5. Model Evaluation
6. Prediction

Before providing the sample code for predicting the color attribute, I experimented with two methods for attribute prediction:-
1. Training the model on all five attributes (color, sleeves, neck type, pattern, size) together and predicting the result.
2. Training the model on each attribute individually and obtaining the result.
   
After conducting these experiments, I discovered that the second method yielded higher accuracy compared to the first. Therefore, I have included the sample code for predicting a single attribute (color) above.

Bonus Point: In addition to the ResNet model and other alternatives, consider exploring Vit-B32 as a potential option to improve attribute prediction accuracy ;D

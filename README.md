# Amazon-Fine-Food-Review
Experimenting with Amazon Fine Food Review data

## Objectives:
1. To build a review summarizer which takes reviews of products at Amazon and summarizes that.
2. To build a model which takes reviews of products at Amazon and classifies it into whether the review is positive or negative.

### Source of Data:
https://www.kaggle.com/snap/amazon-fine-food-reviews

### Area of Improvement:

For Summarizer:
1. Need to **increase the training dataset** size and build the model so that the generalization capability of a deep learning model enhances with an increase in the training dataset size

2. Need to implement **Bi-Directional LSTM** which is capable of capturing the context from both the directions and results in a better context vector

3. Need to use the **beam search strategy** for decoding the test sequence instead of using the greedy approach (argmax)

4. Try evaluating the performance of your model based on the **BLEU score**

5. I can also implement **pointer-generator networks** and **coverage mechanisms**

For Classifire:
1. Can use **Boosting Models** for better performance
2. Can experiment with **Neural Network** for better classification

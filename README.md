# frauddetection
Fraud Detection Using XGboost and Logistic Regression


Abstract - Credit cards are used as a payment method worldwide. Excellent facilities are offered by credit cards for both buying and selling transactions. The downside is it has fraud problems that result in significant financial losses to companies each year. Throughout the year different ways to confront fraud have been made and improved upon. The most noticeable method being Machine Learning (ML). In this paper, we will be improving credit card fraud through Logistic Regression, an algorithm for machine learning, using the XGBoost boosting algorithm. A dataset from Kaggle will be used for this. We will use confusion matrix, precision, recall, f1 and roc-auc-score to assess the performance of the 

Introduction
Credit card fraud detection works by identifying irregularities or patterns in transaction history that indicate fraudulent activity. However imbalanced datasets, where fraudulent transactions are not the majority, make it challenging for different methods to accurately identify fraud[1].

Credit-card fraud can be done in two ways  either offline or online . Offline fraud is typically done by having a stolen physical credit card from a client and using it for physical purchases [2].Online fraud occurs when the client's credit card information is compromised and then the card is used for digital purchases [2]. 

It is important to collect key details for reasons of fraud to avoid losses for clients and card issuers. This information is needed to help figure out where holes exist in the security issues in the credit card industry.

In 2015 credit card fraud cost clients and organizations a lost sum of $21.84 billion, with card issuers covering $15.72 billion of the cost [2]. With such  large losses the need for efficient sources of credit card fraud detection is great.

Traditionally, financial institutions have depended on the insight, expertise, and specialized knowledge of fraud experts to create rules for identifying fraudulent transactions. However, due to technological advancements, the vast amount of data produced by numerous transactions, and the growing sophistication of fraudsters, maintaining such a rule-based detection system has become increasingly challenging. Consequently, machine learning algorithms are now being employed to construct models that effectively detect fraudulent credit card transactions.[3]

Problem Identification

There is a problem of efficiency of credit card fraud detection, the common methods of detection being used are not efficient enough. In fraud detection, methods like fuzzy logic based system, decision tree,  neural network systems and the  hidden markov model (HMM) are utilized. 

Some of these methods are accurate but not efficient for example the neural network system method of detection is accurate but also very costly due to its complexity making it inefficient[4]. While others like the hidden markov model are fast and inexpensive but are not accurate also making this method of fraud detection inefficient [5].
 In this paper we implemented decision tree-based XGBoost and logistic regression, and we demonstrated it with precision, recall, and F1 score

Related Work

The detection of credit card fraud using machine learning techniques has gained significant attention in recent years, as evidenced by numerous studies. These studies employ various machine learning and deep learning algorithms to tackle the problem, given the complexity and evolving nature of fraud tactics.
In the domain of credit card fraud detection, machine learning algorithms like logistic regression, decision trees, support vector machines (SVM), random forests, and deep learning models are commonly used due to their effectiveness in pattern recognition and anomaly detection [6]. Specifically, logistic regression and AdaBoost have been highlighted for their superior performance in detecting fraud compared to other algorithms like Naïve Bayes and J48 [7]. Additionally, oversampling techniques are utilized to address the challenge of imbalanced datasets, which is common in fraud detection scenarios, ensuring that the machine learning models are not biased towards the majority class[8]
Deep learning techniques, which involve the use of neural networks with multiple layers, are particularly noted for their ability to automatically extract and learn features from data, providing a deeper insight for fraud detection[9]. These methods have been compared with traditional machine learning techniques to evaluate their efficacy in identifying fraudulent transactions with high accuracy.
A comparative analysis of various machine learning and deep learning techniques underscores the importance of selecting appropriate algorithms based on the specific characteristics of the dataset and the nature of the fraud detection problem[10]. The research highlights the evolving landscape of credit card fraud detection, emphasizing the need for continuous adaptation and improvement of models to effectively combat fraud.
Moreover, some studies focus on the use of hybrid models that combine multiple machine learning algorithms to enhance detection rates and reduce false positives, illustrating the dynamic and multifaceted approach required in the field[11].
In summary, the body of work surrounding credit card fraud detection with machine learning showcases a broad array of techniques aimed at optimizing fraud detection systems. The ongoing research and development in this area reflect the critical nature of credit card fraud detection in ensuring secure transactions and maintaining consumer trust in financial systems.

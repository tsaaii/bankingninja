# bankingninja
A sample machine learning algorithm to detect fraudulent activities on a credit card


How a fradulent case is identified by banks?

from a bit of googling, reading few research papers and a good youtube video, My primary observation is with a thorough process of analyzing credit card transactions,recognizing patterns and spending profiles, credit card companies will identify transactions that are fraud.

The easiest way that credit card companies identify credit card fraud is by recognizing a break in spending patterns.  For example, if you live in waterloo, ontario and suddenly your card is used to buy something in vancouver, BC – that may tip the scales in favor of possible fraud, and your credit card company might decline the charges and ask you to verify them.

Examples of how these patterns work:

Location: Live in one place but make a purchase in another.

What you buy: If your card is commonly used to buy your morning cup of coffee and then a tank of gas, and out of the blue is used to buy a pair of expensive designer shoes.

Spending amount: If you typically spend $500 / month, and suddenly rack up $3000 in a week.

Spending frequency: If your card is used to make a large number of purchases over a short period of time.

Large purchase after a smaller one: Thieves typically test stolen credit cards with smaller purchases first, such as a song from iTunes; if the card works, they will proceed to make another larger purchase, like an expensive camera, or television, or sound system.

Digital origins: Ecommerce makes it easy for us to make purchases, but it also makes it easy for thieves to commit fraud; the digital origins of purchases are recorded and analyzed with each purchase; if an IP address had been used to commit fraud in the past, subsequent transactions from the same IP or network may be flagged.

what might be banks using?

1. clustering (mapping and linking common purchase attempts together).
2. classification (labeling purchases in respect to their characteristics, like location, time, fraud probability, etc)
3. averaging to determine patterns of behavior.
4. segment the data and automatically find associations and rules in the data that may signify interesting patterns, including those      related to fraud.
5. Expert systems to encode expertise for detecting fraud in the form of rules.
6. Pattern recognition to detect approximate classes, clusters, or patterns of suspicious behavior either automatically (unsupervised) or to match given inputs.
7. Machine learning techniques to automatically identify characteristics of fraud.
8. Neural networks that can learn suspicious patterns from samples and used later to detect them.
9. Other techniques such as link analysis, Bayesian networks, decision theory, and sequence matching are also used for fraud detection.

#Types of learning in this case:

In #supervised learning, a random sub-sample of all records is taken and manually classified as either 'fraudulent' or 'non-fraudulent'. Relatively rare events such as fraud may need to be over sampled to get a big enough sample size. These manually classified records are then used to train a supervised machine learning algorithm. After building a model using this training data, the algorithm should be able to classify new records as either fraudulent or non-fraudulent.
Supervised neural networks, fuzzy neural nets, and combinations of neural nets and rules, have been extensively explored and used for detecting fraud in mobile phone networks and financial statement fraud.
Bayesian learning neural network is implemented for credit card fraud detection, telecommunications fraud, auto claim fraud detection, and medical insurance fraud.

Hybrid knowledge/statistical-based systems, where expert knowledge is integrated with statistical power, use a series of data mining techniques for the purpose of detecting cellular clone fraud. Specifically, a rule-learning program to uncover indicators of fraudulent behaviour from a large database of customer transactions is implemented.

Cahill et al. (2000) design a fraud signature, based on data of fraudulent calls, to detect telecommunications fraud. For scoring a call for fraud its probability under the account signature is compared to its probability under a fraud signature. The fraud signature is updated sequentially, enabling event-driven fraud detection.

Link analysis comprehends a different approach. It relates known fraudsters to other individuals, using record linkage and social network methods.This type of detection is only able to detect frauds similar to those which have occurred previously and been classified by a human. To detect a novel type of fraud may require the use of an unsupervised machine learning algorithm.

#Unsupervised learning

In contrast, unsupervised methods don't make use of labelled records.
Some important studies with unsupervised learning with respect to fraud detection should be mentioned. For example, Bolton and Hand use Peer Group Analysis and Break Point Analysis applied on spending behaviour in credit card accounts. Peer Group Analysis detects individual objects that begin to behave in a way different from objects to which they had previously been similar. Another tool Bolton and Hand develop for behavioural fraud detection is Break Point Analysis. Unlike Peer Group Analysis, Break Point Analysis operates on the account level. A break point is an observation where anomalous behaviour for a particular account is detected. Both the tools are applied on spending behaviour in credit card accounts.

Also, Murad and Pinkas focus on behavioural changes for the purpose of fraud detection and present three-level-profiling. Three-level-profiling method operates at the account level and points to any significant deviation from an account's normal behaviour as a potential fraud. In order to do this, 'normal' profiles are created based on data without fraudulent records (semi supervised). In the same field, also Burge and Shawe-Taylor use behaviour profiling for the purpose of fraud detection. However, using a recurrent neural network for prototyping calling behaviour, unsupervised learning is applied.

Cox et al. combines human pattern recognition skills with automated data algorithms. In their work, information is presented visually by domain-specific interfaces, combining human pattern recognition skills with automated data algorithms (Jans et al.).






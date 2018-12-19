# Toxic-Comment-Classification-

1.	Problem statement

The Conversation AI team, a research initiative founded by Jigsaw and Google (both a part of Alphabet) are working on tools to help improve online conversation.

Discussing things you care about can be difficult. The threat of abuse and harassment online means that many people stop expressing themselves and give up on seeking different opinions. The current models still make errors, and they don’t allow users to select which types of toxicity they’re interested in finding.

In this competition, challenge is to build a multi-headed model that’s capable of detecting different types of of toxicity like threats, obscenity, insults, and identity-based hate better than Perspective’s current models.




2.	Data Description.


2.1	Toxic: All other categories, like, ‘sorry’, ‘thanks’ or any general discussion fell under toxic class. This made one to be difficult to find a particular pattern and hence to classify it properly.

2.2	Severe toxic: The text containing offensive and hurtful words had been classified as severe toxic.

2.3	Obscene: The text containing vulgar and offensive words was labelled as obscene.

2.4	Threat: If a text contains words like ‘kill’, ‘shoot’, ‘murder’, or ‘gun’, then it was labelled as a threat.

2.5	Insult: This class is interesting. If hurtful words were shot at some person, then those texts were classified as an insult, that is, the texts containing a noun or a pronoun together with vulgar or offensive or hurtful words were labelled as an insult.

2.6	Identity_hate: If a text points out at some community or a religion, like, ‘Nigerian', 'Jews', 'Muslim' or 'gay', then it was labelled as identity-hate.



3.	File description


•	train.csv - the training set, contains comments with their binary labels.

•	test.csv - the test set, you must predict the toxicity probabilities for these comments. To deter hand labeling, the test set contains some comments which are not included in scoring.

•	submission.csv - a  submission file in the correct format with “solver = liblinear”.

•	Submission1.csv - a  submission file in the correct format with “solver = sag”.

•	Liblinear.png - cv scores for solver = liblinear.

•	Solver.png – cv scores for solver = sag.

•	Sourcecode.py – source code.

•	Result = important words and its frequency as result.csv





 

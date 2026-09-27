# AI_From_Scratch
Building ML concepts from scratch, derivatives by hand, and theory by reading. Part of a 12-project curriculum I built for myself.
*NOTE: None of the resources I reference explicitly show code to copy or walk you through it. So my work is all personal testing after learning intuition and math.*
## Disclaimer: For the purpose of learning, I don't use any AI to write code. Occasionally, I use it to walk through complex concepts (I'll specify when), but never to write code.
# Project 1 - Linear Regression
<img width="414" height="310" alt="Screenshot 2026-09-18 203649" src="https://github.com/user-attachments/assets/61019c16-408a-4faa-8b49-74f60b633ad5" />

Built my own linear regression setup from scratch.
I used the following resources to better understand linear regression:
https://www.youtube.com/watch?v=3dhcmeOTZ_Q
https://medium.com/data-science/implementing-linear-regression-with-gradient-descent-from-scratch-f6d088ec1219

This code showcases:
libs: pyplot, random
concepts: regression, SSE, SE, MSE, gradients for MSE, partial derivatives, gradient descent.

# Project 2 - Logistic Regression
<img width="425" height="322" alt="Screenshot 2026-09-18 203731" src="https://github.com/user-attachments/assets/b48c5c9f-c171-46db-8f03-8a12748f0205" />

Built my own logistic regression setup from scratch.
I used the following resources to better understand linear regression and the other related topics.
https://www.youtube.com/playlist?list=PLuhqtP7jdD8Chy7QIo5U0zzKP8-emLdny (Playlist, excluding code implementation video)
https://www.youtube.com/watch?v=yyv_WcepXm0&t=475s
https://www.youtube.com/watch?v=yIYKR4sgzI8&t=316s
https://developers.google.com/machine-learning/crash-course/classification/accuracy-precision-recall
Other sources include Google search and several discussions on the logic behind Convexity, the usage of Logarithms in cross-entropy loss, and Sigmoids.

This code showcases:
libs: numpy, pylot, random
concepts: regression, cross-entropy loss (CSE), convexity, logarithms in loss functions, gradients for cross-entropy, sigmoid differentiation, logistic function, partial derivatives, gradient descent, permutation data shuffling, F1/precision/recall

# Project 3 - K Nearest Neighbor
<img width="415" height="305" alt="Screenshot 2026-09-26 193933" src="https://github.com/user-attachments/assets/b0c332c6-e1fe-40b0-ae57-4025445ca3a4" />

Built my own K nearest neighbor, or KNN, classifier from scratch
I used the following resources to learn the required concepts to build this classifier.
https://www.youtube.com/watch?v=BR3Qx9AVHZE&t=2s
https://www.youtube.com/watch?v=e9U0QAFbfLI
https://www.youtube.com/watch?v=aBgMRXSqd04&t=1s
https://towardsdatascience.com/curse-of-dimensionality-an-intuitive-exploration-1fbf155e1411/
A lot of the concepts I learned were through Google searches and Gemini AI responses, as they taught me a lot. This was helpful for quickly asking questions. Just wanted to say.
This code showcases:
libs: numpy, pyplot, random, time
concepts: inference-only classifier, L1/L2/L... norm, cosine similarity, vectorization, broadcasting, Curse of High Dimensions, Lots of linear algebra conceptually, nearest neighbor classification.

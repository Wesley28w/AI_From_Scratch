# AI_From_Scratch
Building ML concepts from scratch, derivatives by hand, and theory by reading. Part of a 12-project curriculum I built for myself.
*NOTE: None of the resources I reference explicitly show code to copy or walk you through it. So my work is all personal testing after learning intuition and math.*
#### Disclaimer: For the purpose of learning, I don't use any AI to write code. Occasionally, I use it to walk through complex concepts (I'll specify when), but never to write code.
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

# Project 4 - PCA and SVD
<img width="441" height="347" alt="Screenshot 2026-10-18 200211" src="https://github.com/user-attachments/assets/7fee1049-de0f-4bbb-b861-349160c1f75b" />

Built my own Principal Component Analysis System that uses SVD or maximizes the covariance matrix to identify the principal components of a dataset. This preprocessing tool is used during pretraining to simplify training data by identifying which components matter.
To build this, I went back and spent significant time improving my skills in Linear Algebra, though I still have much to learn. That is the reason it took 3 weeks instead of 1 for this project.
I watched this excellent Linear Algebra Course from Dr. Trefor Bezett and took over 70 pages of notes (and yes watched all 84 videos). I will likely need to continue with an additonal course to further solidfy my knowledge and fill in gaps.
Lin alg course: https://www.youtube.com/playlist?list=PLHXZ9OQGMqxfUl0tcqPNTJsb7R6BqSLo6
I also used Gemini Google Search a lot for quick understanding validation.
Here are additional recourses I used:
https://www.youtube.com/watch?v=fkf4IBRSeEc
https://www.youtube.com/watch?v=ZgyY3JuGQY8
https://www.youtube.com/watch?v=FgakZw6K1QQ&t=3s
https://www.youtube.com/watch?v=FD4DeN81ODY
https://www.youtube.com/watch?v=ZgyY3JuGQY8
https://www.youtube.com/watch?v=_YPScrckx28
I found this guy who is a gem (like 3blue1brown): *he connected many dots for me*
https://www.youtube.com/watch?v=7Gtxd-ew4lk
https://www.youtube.com/watch?v=mhy-ZKSARxI
https://www.youtube.com/watch?v=vSczTbgc8Rc&pp=0gcJCUcMAYcqIYzv

This code showcases:
libs: numpy, pyplot. I also learned sklearn is a popular library so I may check out soon, especially as datasets grow in complexity.
concepts: **linear algebra**, SVD, PCA, orthogonality, diagonalization, symmetry, matrix decomposition, projection, eigenvalues/eigenvectors, basis, multi-dim linear regression, transpose, just a ton of linear algebra really. The code itself wasn't very long. 
I found three main ways to identify the eigenvalues/eigenvectors which serves as the variance and pricipal components:
1. Maximize the variance of the projected points onto a line (I did this)
2. Use Singular Value Decomposition to identify the orthogonal matrix V^t. (I did this)
3. Multi-dim linear regression by minimizing residuals. Very over-engineered. I didn't do this. Maybe another time.

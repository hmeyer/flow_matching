# flow_matching
Flow Matching Experiments using MNINST.

![image](animated_mnist.gif)


This repo contains ipython notebooks that demonstrate Flow Matching and Discrete Flow Matching, both along with scorer guidance.
The focus of the notebooks is to be instructive and fast, to allow for quick experimentation.
We use the MNIST dataset b/c it is simple.

Furthermore we use scorer guidance to generate brighter/darker digits:
![image](https://github.com/user-attachments/assets/5480a288-9c45-4aca-abdd-20d21f1023dd)

Using a trained classifier as guidance scorer we can generate specific digits from our unconditional model.
![image](https://github.com/user-attachments/assets/44f111fe-b85c-4a79-bf37-ede391406646)


Scorers can also be combined.</br>
![image](https://github.com/user-attachments/assets/886d4eb4-54bd-49d9-b0d6-23fc89283585)


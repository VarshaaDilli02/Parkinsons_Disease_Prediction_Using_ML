# PARKINSONS DISEASE PREDICTION USING ML

Parkinson’s disease is a progressive disorder that affects the nervous system and the parts of the body controlled by the nerves. Symptoms are also not that sound to be noticeable. Signs of stiffening, tremors, and slowing of movements may be signs of Parkinson’s disease. This project classifies the patient with disease from the healthy patients.

## Aim

To classify patients with Parkinson's disease based on different features and use different machine lerning models to preict the presence of the disease in an individual.

## Scope

This will be helpful for the patients in the early detection of the disease.


## Dataset

•	The dataset was downloaded from Kaggle.

•	The attributes include name, MDVP:Fo(Hz), MDVP:Fhi(Hz), MDVP:Flo(Hz), MDVP:Jitter(%), MVDP:Jitter(Abs), MDVP:RAP, MDVP:PPQ, NHR, HNR, status, RPDE, DFA, spread1, spread2, D2 and PPE.


## Languages Used

•	Python


## Concepts Used

•	ML models

Logistic Regression

Naive Bayes Classifier

Support Vector Machine

Decision Tree Classifier

Random Forest Classifier

## Accuracy

SUPPORT VECTOR MACHINE MODEL was found to be the best model with the accuracy of 89.74%.


```mermaid
graph TD;
    Register["( Register )"] -->|Name, email, password| Register
    Register -->|Saved successfully| Login
    Login["( Login )"] -->|Email, password| Login
    Login -->|Successful login| User
    Login -->|Access rights| Admin
    Login -->|User data| Users
    Users["( Users )"] -->|Manage user| Admin
    Users -->|User list| Admin
    Users -->|d_users| Login
    Materials["( Materials )"] -->|Manage material| Admin
    Materials -->|View material| User
    Materials -->|Save material| Materials
    Materials -->|Saved successfully| Materials
    Materials -->|material| User
    Exercises["( Exercises )"] -->|Manage exercises| Admin
    Exercises -->|Save exercises| Exercises
    Exercises -->|Saved successfully| Exercises
    Exercises -->|exercise| User
    Exercises -->|d_contents| Materials
    Contents["( Contents (Images & Videos) )"] -->|Manage video and image content| Admin
    Contents -->|Save video, image (url)| Contents
    Contents -->|Saved successfully| Contents
    Contents -->|Video and image content| User
    Admin["[ Admin ]"] -->|email, password| Login
    Admin -->|material| Materials
    Admin -->|exercises| Exercises
    Admin -->|Video and image content| Contents
    User["[ User ]"] -->|View material| Materials
    User -->|Lihat exercise| Exercises
    User -->|View video and image content| Contents
```



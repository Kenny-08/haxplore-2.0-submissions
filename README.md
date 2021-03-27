# HaXplore 2.0 - Submission Report Format

This is the official code repository for _That_One_Guy_ . This _"Traceability of Organic Food
" Web App_ was developed during HaXplore 2.0, 
the online hackathon conducted by Codefest, the annual departmental fest of Computer Science department, IIT BHU Varanasi.

### _Team Name_

* _Kenny Patel_
* _Diya Agrawal_

#### _Traceability of Organic Food_


#### Overview

One of the significant concerns with organic food supply systems is to build trust in users about the authentication of ingredients. 

This involves the following major issues:

* Whether the ingredients that the producer claims are actually used in the product.
* Whether there is some ingredient (which might be harmful) present in the food but is not listed/informed by the producer.
* Whether the ingredients meet some quality standard.
 
Our idea is to create a system that ensures all the above-mentioned issues. 

We propose a system that uses a machine learning based model that detects the ingredients present in the food through its image. The ingredients are ensured at the consumer end as well as the producer end to ensure transparency. We also maintain a check that ensures that the ingredients meet the quality standards, by comparing the ingredients detected by the algorithm with the quality standard requirements.
.

#### Technology used

- Spring
- Machine Learning

#### Screenshots/Demo Video

_Add some screens and a demo_

#### Usage

* Quality Standards are generated and stored.
* The producer uploads the ingredients they use in making the product.
* The ingredients are tested against the quality standards and rejected if they do not follow the standards. 
* If the ingredients pass the quality standards, the producer produces the food product and sends it to be delivered to the customer.
* Before delivery, the supplier uploads an image of the product.
* A Machine learning model detects the ingredients present in it and compares them with the quality standards and the ingredients claimed by the producer in step 2.
* If successful, the consumer gets notified that the product is good to take.
* Then, the consumer takes the food and uploads its image, and the ingredients check mentioned in step 6  is performed again. This ensures that the food was not altered after check by the supplier and before the consumer receives it.
* [This](https://www.researchgate.net/publication/312344611_Machine-Learning_models_to_predict_the_antioxidant_capacity_of_food) paper discusses the ML model that can be used for predicting ingredients


#### Tracks used

[Amazon Web Services Track](https://docs.google.com/document/d/16wxLl_8Eqw_bcjY28FnP3bc2YihB6pCN5aPAmF5An_o/edit?usp=sharing)


#### AWS Services Used

_Write in brief about how you used AWS service to improve your application._





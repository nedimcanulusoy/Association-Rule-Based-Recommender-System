<div style="font-style: bold; text-align: center;" markdown="1">

## Association Rule Based Recommender System 

</div>

---

### Problem

Armut is one of the largest online service platforms in Turkey and it brings together service providers and those who
want to receive service. It provides easy access to services such as cleaning, modification and transportation with a
few touches on your computer or smartphone.

It is desired to create a product recommendation system with Association Rule Learning by using the data set containing
the service users and the services and categories these users have received.

---

### Dataset

The data set consists of the services customers receive and the categories of these services. Date and time of each service received
contains information.

There are `4 different variables` and `162.523 observations` in the dataset.

    UserId         : ID of the user
    ServiceId      : Anonymized services belonging to each category (Example: Upholstery washing service under the cleaning category)
                     A ServiceId can be found under different categories and refers to different services under different categories.
                     (Example: The service with CategoryId 7 and ServiceId 4 is heater cleaning, while the service with CategoryId 2 and ServiceId 4 is furniture assembly)       
    CategoryId     : Anonymized categories (Example: Cleaning, transportation, renovation category)
    CreateDate     : The date the service was purchased

---

### Installation

1. Clone this repository

```
https://github.com/nedimcanulusoy/Association-Rule-Based-Recommender-System
```

2. Change directory to the cloned repository

```
cd Association-Rule-Based-Recommender-System
```

3. Open the notebook and run the cells

---

### Disclaimer

The data set is not included due to General Data Protection Regulation (GDPR) rules.

---

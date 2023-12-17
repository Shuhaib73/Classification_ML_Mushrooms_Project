<p style='text-align: center'>
  <h1>Mushroom Classification Project</h1>
</p>

<p align='center'>
  <img src='https://github.com/Shuhaib73/Classification_ML_Mushrooms_Project/blob/main/mus_ims.jpg' />
</p>


*Description*

* *Our task resolves around a dataset provided by researchers from the University of California, Irvine.*
* *This dataset encapsulates detailed information on 23 mushrooms species, each belonging to the Agaricus and Lepiota Family Mushrom categories.*
*For each species, the dataset classifies them as either edible or poisonous, or of unkown edibility and not recommended. notably, the latter category has been merged with the poisonous one.*
* *Our objective is to develop a machine learning classification model capable of predicting whether a given mushroom is poisonous or edible based on provided features.*


### **Attribute Information**
**Target Variables**
* **classes : edible = e and poisonous = p**
### **Features**
* **cap-shape**: bell=b, conical=c, convex=x, flat=f, knobbed=k, sunken=s
* **cap-surface**: fibrous=f, grooves=g, scaly=y, smooth=s
* **cap-color**: brown=n, buff=b, cinnamon=c, gray=g, green=r, pink=p, purple=u, red=e, white=w, yellow=y
* **bruises**: bruises=t, no=f
* **odor**: almond=a, anise=l, creosote=c, fishy=y, foul=f, musty=m, none=n, pungent=p, spicy=s
* **gill-attachment**: attached=a, descending=d, free=f, notched=n
* **gill-spacing**: close=c, crowded=w, distant=d
* **gill-size**: broad=b, narrow=n
* **gill-color**: black=k, brown=n, buff=b, chocolate=h, gray=g, green=r, orange=o, pink=p, purple=u, red=e, white=w, yellow=y
* **stalk-shape**: enlarging=e, tapering=t
* **stalk-root**: bulbous=b, club=c, cup=u, equal=e, rhizomorphs=z, rooted=r, missing=?
* **stalk-surface-above-ring**: fibrous=f, scaly=y, silky=k, smooth=s
* **stalk-surface-below-ring**: fibrous=f, scaly=y, silky=k, smooth=s
* **stalk-color-above-ring**: brown=n, buff=b, cinnamon=c, gray=g, orange=o, pink=p, red=e, white=w, yellow=y
* **stalk-color-below-ring**: brown=n, buff=b, cinnamon=c, gray=g, orange=o, pink=p, red=e, white=w, yellow=y
* **veil-type**: partial=p, universal=u
* **veil-color**: brown=n, orange=o, white=w, yellow=y
* **ring-number**: none=n, one=o, two=t
* **ring-type**: cobwebby=c, evanescent=e, flaring=f, large=l, none=n, pendant=p, sheathing=s, zone=z
* **spore-print-color**: black=k, brown=n, buff=b, chocolate=h, green=r, orange=o, purple=u, white=w, yellow=y
* **population**: abundant=a, clustered=c, numerous=n, scattered=s, several=v, solitary=y
* **habitat**: grasses=g, leaves=l, meadows=m, paths=p, urban=u, waste=w, woods=d

### Conclusion:
      * The machine learning models assessed on this dataset demonstrated exceptional performance with nearly 100% accuracy, precision, and recall scores.*
      * To determine the most efficient model amonth them, we leveraged the 'time' package and employed the 'time()' function to measure the total time consumed by each algorithm in predicting both training and testing datasets.*
      * Among the various models assessed, the **XGBClassifier** stood out as the most efficient, requering the least amount of time for prediction.*

### Interpretation:

      * The precision, recall, and F1-score for both classes (0 and 1) are 100%, which indicates perfect performance on both classes.
      * The accuracy Score is 100%, meaning that the model correctly classified all the instances in the dataset.*

### Confusion Matrix:

    * The Confusion matrix shows the number of True positive (TP), True negative (TN), False positive (FP), and False negative (FN) Predictions.*
    * For Testing dataset, Confusion matrix showed that there were 845 true positives (Correctly predicted Edible Mushrooms) and 780 True negatives (correctly predicted Poisonous Mushrooms).*



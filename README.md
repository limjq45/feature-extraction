# 33onethird
Follow up to the DREBIN paper

---

This is a students project at the WU Vienna trying to replicate and improve upon the [DREBIN][1] paper.
It requires:
  * the original dataset for the replication and a new dataset for modern evaluation
  * the extraction of the same or more features from APKs
  * recreation of the Support Vector Machine(SVM).

This is followed by machine learning with [**TensorFlow**](https://www.tensorflow.org/) and subsequent testing of the proficiency of the resulting program. 

### Requirements
The Feature Extractor needs Java 8 or higher installed. To install it on Ubuntu:
`sudo apt-get install openjdk-8-jre icedtea-8-plugin`

To use the feature extractor, call
`java -jar [input] [output]`
where `output` and `input` can be a directory of `.apk` files or and `apk` file.


### Results
Will be added when available

### Namesake
Our repository heavily revolves around the infamous [DREBIN][1] paper, which shares the name with a beloved Leslie Nielsen character from the filmseries "The Naked Gun". The movie lives off of slapstick and puns, much like we do.

### References
[1]: https://www.researchgate.net/publication/264785935_DREBIN_Effective_and_Explainable_Detection_of_Android_Malware_in_Your_Pocket
Arp, Daniel & Spreitzenbarth, Michael & Hübner, Malte & Gascon, Hugo & Rieck, Konrad. (2014). DREBIN: Effective and Explainable Detection of Android Malware in Your Pocket.

Martín García, Alejandro & Menéndez, Héctor & Camacho, David. (2017). String-based Malware Detection for Android Environments.

Ambra Demontis, Marco Melis, Battista Biggio, Davide Maiorca, Daniel Arp, Konrad Rieck, Igino Corona, Giorgio Giacinto, Fabio Roli. (2017). Yes, Machine Learning Can Be More Secure! A Case Study on Android Malware Detection.

Feng, Yu & Anand, Saswat & Aiken, Alex & Dillig, Isil, (2014), Apposcopy: Semantics-Based Detection of Android Malware through Static Analysis

Batyuk, Leonid & Herpich, Markus & Camtepe, Seyit & Raddatz, Karsten & Schmidt, Aubrey-Derrick & Albayrak, Sahin, (2011), Using Static Analysis for Automatic Assessment and Mitigation of Unwanted and Malicious Activities Within Android Applications

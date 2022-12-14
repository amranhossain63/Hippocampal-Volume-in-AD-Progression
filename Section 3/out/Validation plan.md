Validation plan

What is the intended use of the product?

The algorithm is intended for use to assist radiologists in quantifying hippocampus volume.


About the training data Collection:

The dataset is collected from the "Hippocampus" dataset from the Medical Decathlon competition: http://medicaldecathlon.com. 
The dataset consists of 263 training and 131 testing images.
We used cropped volumes of these images where only the region around the hippocampus has been cut out.


Data Labeling:
All data has been labeled and verified by Radiologists

About the training performance of the algorithm measured:
The performance was measured with Jacard and Dice scores

Real-world performance to be estimated: 
The real world performance of the algorithm could be estimated by validating the model on more datasets


The data will the algorithm perform well in the real world and what data it might not perform well on:
The dataset did not include much information about the patient (age, gender or conditions, ...).
This might have an impact on the performance of the algorithm.
The algorithm should have a good performance in images of human brains with a clear view of the hippocambus.

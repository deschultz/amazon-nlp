# Amazon NLP - Project Goals
Dylan Schultz, Federico Scivittaro, Ryan Sullivan


# Datasets

# Modeling Strategy
We begin by taking the pre-labeled training data (see *Datasets*), which contains Amazon product reviews labeled as either positive or negative, and load them into Amazon Comprehend (https://docs.aws.amazon.com/comprehend/latest/dg/what-is.html) to produce a model that can take in future product reviews and classify them as positive or negative. Then, we qualitatively examine the results of the Comprehend modeling processes and examine the extent to which its classifications are logical.

Once that task is finished, we construct our own topic modeler using either Latent Dirichlet Allocation or Neural Topic Modeling. We will take the same data set, train our own model on it, and then compare its classifications (positive or negative) to those of Comprehend. The goal should be to produce a model that is at least as accurate, if not more accurate, than the Comprehend model.

# End Goal
The end goal of our project is to create a topic modeling algorithmn that will output more logical topics than those created by Amazon's Comprehend. 
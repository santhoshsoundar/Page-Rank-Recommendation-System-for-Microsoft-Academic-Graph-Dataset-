# Page-Rank-Recommendation-System-for-Microsoft-Academic-Graph-Dataset-
This is project submitted as a part of Big Data Analytics ILS - Z604 Course at IU


##### Task: Predict Papers with most relevant Keywords
###### In this task, given a paper id, we try to predict key words that the paper can be tagged with. To run the below given python files, the PaperCollection.json is required to compute page rank on the 100000 paper records present in it. 

			Important Files :
			PageRank_Rec.py:-  Implements Page Rank and compute most relevant paper keywords for a target paper.  
			keyWordCloud.ipynb:- Used to visualize our output pertaining to predicting keywords. 
			PaperCollection.json:- Used for storing the subset of the papers data in the .json format.
			buildGraphFromPy.json:-Used for build a graph based on schema designed from the .py env. 

##### Evaluation:
We computed the precision recall measures for this task and found some unstable results since the data under consideration is a subset and building a ground truth on this sub-set either gave us exact match of 100\%, 50\% or no match in most of the cases since we found only 1 or 2 PRefIds for the ground truth which can either be present in the predicted list or not be present.


# 2017---Deep-learning-yeast-UTRs

# Code from Deep Learning Of The Regulatory Grammar Of Yeast 5' Untranslated Regions from 500,000 Random Sequences
We hope that by including some of the code in our analysis it will help others repeat and build on our results. Hopefully this will be useful, and feel free to contact me if you have any questions/concerns/suggestions. -Ben

To get going, just put the Data and Jupyter_notebooks folders into the same folder. If you start with Notebook_1 everything should just work (including the creation of subsequent folders/subfolders). If you'd like to just go through a specific notebook without running the others, let me know and I can provide the required files (bgroves "at" uw "dot" edu, or benjaminbgroves "at" gmail "dot" com).




## Jupyter notebooks:
[Notebook 1 - training a CNN on random 5\'92 UTR data along with hyper-parameter search](./Jupyter_notebooks/Notebook_1_CNN_Model_Training_with_Hyperparameter_Search.ipynb)

[Notebook 2 - CNN predictions of random 5\'92 UTR growth rates](./Jupyter_notebooks/Notebook_2_CNN_Predictions_of_Random_UTR_HIS3_data.ipynb)

[Notebook 3 - CNN predictions of native 5\'92 UTR growth rates](./Jupyter_notebooks/Notebook_3_CNN_Predictions_of_Native_UTR_HIS3_data.ipynb)

[Notebook 4 - Model-directed evolutions of highly-expressing 5' UTRs from 100 native and 100 random 5' UTR sequences](./Jupyter_notebooks/Notebook_4_Generating_Model_Directed_Evolution_of_UTRs_From_100_Native_and_Random_UTRs.ipynb)




## Requirements:
We performed the model training on either a server with dedicated GPUs here at UW, or one of the machine learning/neural network instances on Amazon Web Services. I would recommend going this route, as using a laptop/desktop CPU may make you want to bang your head against the desk. A normal laptop should be fine for most of the other analysis.




## Versions of Python packages used:
- Keras:		1.2.2
- Theano:		0.9.0
- Hyperopt:	0.1
- Scipy:		0.19.0
- Numpy:		1.12.1
- Pandas:		0.19.2
- Seaborn:	0.8


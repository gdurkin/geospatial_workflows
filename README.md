Some notebooks that might be useful in creating geospatial workflows. 
The goal of the data curation notebook is to leverage the Fused geospatial platform 
and ipyleaflet interactive map tool to generate ML training data (for the task of Crop Detection from Satellite imagery)
There is code also to help with uploading the curated training data to the hugging face cloud platform for ML.

The model training notebook takes this data and finetunes a state of the art transformer model (Mask2Former) 
also from Hugging Face

Finally, the inference notebook takes the finetuned/trained model from hugging face and applies it 
to new imagery in new locations. There are some measurement functions for determining performance, and animations.

Some notebooks that might be useful in creating geospatial workflows. 
The goal of the data curation notebook is to leverage the Fused geospatial platform 
and ipyleaflet interactive map tool to generate ML training data (for the task of Crop Detection from Satellite imagery)
There is code also to help with uploading the curated training data to the hugging face cloud platform for ML.

The model training notebook takes this data and finetunes a state of the art transformer model (Mask2Former) 
also from Hugging Face

Finally, the inference notebook takes the finetuned/trained model from hugging face and applies it 
to new imagery in new locations. There are some measurement functions for determining performance, and animations.

![earth_smoking](https://github.com/user-attachments/assets/3b8e5847-3111-4cc8-b2fc-c43caa4e4eef)

![springfield_sept](https://github.com/user-attachments/assets/ed165f8e-caae-40e8-b11f-c3b633215be6)

![Screenshot from 2024-06-27 12-32-56](https://github.com/user-attachments/assets/860511a8-85d6-4b99-812d-9cdee88ab339)
![springfield_perf](https://github.com/user-attachments/assets/14e2a1dd-abaf-4bba-987c-5422bb9d893e)


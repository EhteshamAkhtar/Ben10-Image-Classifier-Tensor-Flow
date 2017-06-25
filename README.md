# Ben10-Image-Classifier-Tensor-Flow

Classifies a given image as FourArms, Wildmutt,XLR8, GreyMatter or HeatBlast based on the training data of images given in separate folders. 
               
## Retraining Inception:

python retrain.py \
  --bottleneck_dir=bottlenecks \
  --how_many_training_steps=4000 \
  --model_dir=inception \
  --summaries_dir=training_summaries/basic \
  --output_graph=retrained_graph.pb \
  --output_labels=retrained_labels.txt \
  --image_dir=ben10      
  
  ## Testing an image
  python label_image.py _test-image.jpg_
  
  ### Referral source --> https://codelabs.developers.google.com/codelabs/tensorflow-for-poets/ and https://www.youtube.com/watch?v=cSKfRcEDGUs
  
  

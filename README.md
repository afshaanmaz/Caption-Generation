# Caption-Generation

File Structure:

cococaption
sparsemax 
  - core
  - data
      - annotations
          - contains json files for training and validation captions
      - test
          - contains pickle files
      - train
          - contains pickle files
      - val
          - contains pickle files
      - imagenet.mat
  - data_old (shows what .pkl files were available before training)
  - image
      - contains resized images (after preprocessing)
  - jpg
      - contains some results of attention maps
      
  - log (created after training - contains tensorflow logs)
  
  - model
  
  - prepro.py / prepro_small.py
  - resize.py
  - test.py
  - train.py
  
  # large files not included
  (After_training_put_in_data.zip - the fully trained model)

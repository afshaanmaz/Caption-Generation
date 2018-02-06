# Caption-Generation

File Structure:

 - cococaption 
 - sparsemax
 
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

        - log (created after training 
                - contains tensorflow logs)

        - model

        # files

        - prepro.py / prepro_small.py

        - resize.py

        - test.py

        - train.py

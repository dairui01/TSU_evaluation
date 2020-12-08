# Frame-based Evaluation

This code is based on the frame-based evaluation for Charades and MultiThumos ([Link](https://github.com/piergiaj/super-events-cvpr18/blob/master/apmeter.py)).

## Usage 
We provide an example of the predicted logits ([test.pkl](https://mybox.inria.fr/f/a6f4469d3e324c7398ef/?dl=1)). Please download the pickle file and put in this current folder. To run the code, please use the following command: ```python Frame_based_map.py -split CS -pkl_path ./test.pkl```

This code has been tested on python 3.7 and PyTorch 1.2.

## Remarks
1. This code can adapt for different temporal resolusion (number of frames per predicted logit), here we provide the example ```test.pkl``` is in temporal resolusion of 8. To compare with the results reported in the paper, please up-sample the predicted logits to the same temporal resolusion as the ground truth then perform the evaluation. 

3. The provided ```TSU_CS.json```may have slight difference compared to the provided CSV annotation. Please take the CSV format annoatation as the reference. 


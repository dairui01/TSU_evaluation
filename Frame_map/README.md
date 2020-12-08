# Frame-based Evaluation

This code is based on the frame-based calculation for Charades and MultiThumos ([Link](https://github.com/piergiaj/super-events-cvpr18/blob/master/apmeter.py))

## Usage 
We provide an example of the [presicted logits](https://mybox.inria.fr/f/a6f4469d3e324c7398ef/?dl=1). Please download the pickle file and put in this current folder. To run the code using: ```python Frame_based_map.py -split CS -pkl_path ./test.pkl```

## Remarks
1. This code can adapt for different temporal resolusion (frame per prediction), here we provide the example ```test.pkl``` is in temporal resolusion of 8. 

2. To compare with the results reported in the paper, please up-sample the predicted logits to the same temporal resolusion as the ground truth then perform the evaluation. 


If you find this dataset useful for your research, please cite our paper:

	@misc{dai2020toyota,
      title={Toyota Smarthome Untrimmed: Real-World Untrimmed Videos for Activity Detection}, 
      author={Rui Dai and Srijan Das and Saurav Sharma and Luca Minciullo and Lorenzo Garattoni and Francois Bremond and Gianpiero Francesca},
      year={2020},
      eprint={2010.14982},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
	}


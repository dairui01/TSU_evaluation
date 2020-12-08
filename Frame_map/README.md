# Frame-based Evaluation

This code is based on the frame-based calculation for Charades and MultiThumos: [Link](https://github.com/piergiaj/super-events-cvpr18/blob/master/apmeter.py)

To run the code: 

```python Frame_based_map.py -split CS -pkl_path ./test.pkl```

Note that this code can adapt for different temporal resolusion (frame per prediction, fps), here we provide the example ./test.pkl is in temporal resolusion of 8. 

To compare with the results reported in the paper, please up-sample the predicted logits to the same temporal resolusion as the ground truth then perform the evaluation. 


If you find this dataset useful for your research, please cite our paper:

	@misc{dai2020toyota,
      title={Toyota Smarthome Untrimmed: Real-World Untrimmed Videos for Activity Detection}, 
      author={Rui Dai and Srijan Das and Saurav Sharma and Luca Minciullo and Lorenzo Garattoni and Francois Bremond and Gianpiero Francesca},
      year={2020},
      eprint={2010.14982},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
	}


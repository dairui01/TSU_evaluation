# Event-based Evaluation

This code is adapted from [PKUMMD](https://github.com/ECHO960/PKU-MMD/blob/master/evaluate.py).

## Usage
To run this code, you need to prepare the ground truth and the corresponding prediction as in ```./gt``` and ```./pred```. The numbers in the 4 conlomes correspond to: action_index, start time, end time, confidence score.

You can play with:
```python Event_based_map.py -pred_path ./pred -gt_path ./gt -theta 0.3```

## Remarks 
we provide only one videos in this example, which does not cover all the activities in the dataset, thus, while doing mean for the APs, a lot of 0 will be counted.

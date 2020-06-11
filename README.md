## CFML
***Robust visual tracking with correlation filters and metric learning***

**Abstract:** Discriminative correlation filters (DCFs) have been widely used in the visual tracking community in
recent years. The DCFs-based trackers determine the target location through a response map generated
by the correlation filters and determine the target scale by a fixed scale factor. However, the response
map is vulnerable to noise interference and the fixed scale factor also cannot reflect the real scale
change of the target, which can obviously reduce the tracking performance. In this paper, to solve
the aforementioned drawbacks, we propose to learn a metric learning model in correlation filters
framework for visual tracking (called CFML). This model can use a metric learning function to solve the
target scale problem. In particular, we adopt a hard negative mining strategy to alleviate the influence
of the noise on the response map, which can effectively improve the tracking accuracy. Extensive
experimental results demonstrate that the proposed CFML tracker achieves competitive performance
compared with the state-of-the-art trackers.

The matlab code for CFML tracker can be downloaded [here[google]]() or [here[baidu(password)]]().

## Usage
### Tracking
1. If you want to compare our results in your experiment, just download the raw experimental results （coming soon...).
2. If you want to test our experiment:

   2.1 Download the code and unzip it in your computer.
   
   2.2 Run the demo.m to test a tracking sequence using a default model.
   


## Results
| Dataste | OTB2013 | OTB2015 | TC128 |
| --------| --------| ------- | ------ |
| Prec.   | 0.889   | 0.853   | 0.746  |
| AUC     | 0.683   | 0.649   | 0.552  | 


## Citation
If you find the code useful, please cite:
```
@article{yuan2020robust,
  title={Robust visual tracking with correlation filters and metric learning},
  author={Yuan, Di and Kang, Wei and He, Zhenyu},
  journal={Knowledge-Based Systems},
  pages={https://doi.org/10.1016/j.knosys.2020.105697},
  year={2020},
}

```

## Contact
Feedbacks and comments are welcome! Feel free to contact us via dyuanhit@gmail.com


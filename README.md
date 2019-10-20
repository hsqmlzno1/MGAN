# MGAN

Data for our AAAI'19 paper "[Exploiting Coarse-to-Fine Task Transfer for Aspect-level Sentiment Classification](https://arxiv.org/abs/1811.10999)".

#### 2019/02/24 Update: Data resource has been released now! More details will be updated.



# Descriptions

This dataset acts as highly beneficial source domains to improve the learning of more fine-grained aspect-term level (AT) sentiment analysis. The dataset has three characteristics:

#### Large-scale: 100k for each domain

#### Multi-domain: Restaurant, Hotel, Beautyspa

#### Aspect-category (AC): Coarse-grained asepct


Even with a simple attention-based model for the AT task, our method can achieve the STOA performances by leveraging the knowledge distilled from the AC task.

# Data format
Each instance behaves as the format below:

inst1: ID1/sentence1/aspect1/label1

inst2: ID1/sentence1/aspect2/label2

inst3: ID1/sentence1/aspect3/label3

....

The sentence containing multiple aspects are arranged together.

### Example
0H0FwmPY78v_5u51r2TQrw    i did n't dislike the food , but the menu is n't exactly cohesive ... pizza and asian cuisine .	      FOOD_SELECTION    -1 

0H0FwmPY78v_5u51r2TQrw    i did n't dislike the food , but the menu is n't exactly cohesive ... pizza and asian cuisine .	FOOD_FOOD_DISH    -1 

0H0FwmPY78v_5u51r2TQrw    i did n't dislike the food , but the menu is n't exactly cohesive ... pizza and asian cuisine .	RESTAURANT_CUSINE	 -1 

0H0FwmPY78v_5u51r2TQrw    i did n't dislike the food , but the menu is n't exactly cohesive ... pizza and asian cuisine .	FOOD_FOOD	 1 

#### Label Mapping

positive: 1 neutral: 0 negative: -1


# Citation

If the data is useful for your research, please be kindly to give us stars and cite our paper as follows:

```
@article{li2018exploiting,
  title={Exploiting Coarse-to-Fine Task Transfer for Aspect-level Sentiment Classification},
  author={Li, Zheng and Wei, Ying and Zhang, Yu and Zhang, Xiang and Li, Xin and Yang, Qiang},
  journal={arXiv preprint arXiv:1811.10999},
  year={2018}
}
```

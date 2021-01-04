# OPINE
The Dataset for the paper [Open Intent Extraction from Natural Language Interactions](https://dl.acm.org/doi/abs/10.1145/3366423.3380268) (best paper, Web Conference 2020) is shared here.  

## Dataset Description ##

The dataset is a tab-separated text file. Each line of this file contains two columns: ```Inputs``` and ```Intents Labels``` separated by a 'tab'. 

The first column ```Inputs``` contains one or more sentences of Input text. 

The second column ```Intents Labels``` contains human annotated intents for the input text. The number of intents per input text varies from 0 to 3. 

Each intent is a phrase containing an ```ACTION``` phrase and an ```OBJECT``` phrase. For more description of the ```ACTION``` and ```OBJECT``` phrases, please refer to the above mentioned paper. 


If you use this dataset, please cite the following paper:

```
@inproceedings{vedula2020open,
  title={Open Intent Extraction from Natural Language Interactions},
  author={Vedula, Nikhita and Lipka, Nedim and Maneriker, Pranav and Parthasarathy, Srinivasan},
  booktitle={Proceedings of The Web Conference 2020},
  pages={2009--2020},
  year={2020}
}
```

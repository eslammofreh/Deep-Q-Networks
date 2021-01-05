# pytoch-dqn

# Requirements

- python 3.5
- [gym](https://github.com/openai/gym#installation) (built from source)
- [pytorch](https://github.com/pytorch/pytorch#from-source) (built from source)

# Training 

To train a model:

```
$ python main.py

# To train the model using ram not raw images, helpful for testing

$ python ram.py
```

The model is defined in `dqn_model.py`

The algorithm is defined in `dqn_learn.py`

The running script and hyper-parameters are defined in `main.py`

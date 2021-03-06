# PyTorch MNIST Interactive Example

PyTorch MNIST official example with comments & interactive interface.

[深度學習新手村：PyTorch入門（中文）](https://pyliaorachel.github.io/blog/tech/deeplearning/2017/10/16/getting-started-with-deep-learning-with-pytorch.html)

## Structure

```
src/
  train.py    # Train the model
  model.py    # The defined model
  app.py      # Interactive predictor
  model       # Pretrained model, will be overriden when you start training
  test_n.png  # Sample images for the use of interactive predictor
```

## Usage

```bash
# clone project
git clone https://github.com/pyliaorachel/pytorch-mnist-interactive.git
cd pytorch-mnist-interactive

# install dependencies
pip3 install -r requirements.txt

# train & test model
python3 -m src.train
# ...data will be fetched to ../data/
# ...trained model will be saved to ./src/model

# test model interactively
python3 -m src.app --image=<path-to-image>
```

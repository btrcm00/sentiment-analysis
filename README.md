## Sentiment Analysis using PhoBert+Linear

### Model Architecture
- Pretrained model: `vinai/phobert-base-v2`
- Architecture: RobertaForSequenceClassification
- Use Trainer of Huggingface to training model

### Dataset
- Dataset: [30K e-commerce reviews](https://www.kaggle.com/datasets/linhlpv/vietnamese-sentiment-analyst)
- Labels:
    - NEG: Negative
    - POS: Positive
    - NEU: Neutral
 
### Optimization
- Use some optimization techniques to optimize ONNX - [Optim](https://github.com/huggingface/notebooks/blob/main/examples/onnx-export.ipynb)
- See: pipeline/onnx_converter.py


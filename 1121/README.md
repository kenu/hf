# Huggingface
- https://huggingface.co/docs/transformers/installation

```sh
pip install transformers
```

```python
python -c "from transformers import pipeline; print(pipeline('sentiment-analysis')('we love you'))"
```

```python
python -c "from transformers import pipeline; print(pipeline('sentiment-analysis', device=0)('we love you'))" # GPU
```

```python
python -c "from transformers import pipeline; print(pipeline('sentiment-analysis', model='nlptown/bert-base-multilingual-uncased-sentiment')('we love you'))"
```

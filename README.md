---
license: apache-2.0
tags:
- generated_from_keras_callback
model-index:
- name: rahul77/t5-small-finetuned-thehindu
  results: []
---

<!-- This model card has been generated automatically according to the information Keras had access to. You should
probably proofread and complete it, then remove this comment. -->

# rahul77/t5-small-finetuned-thehindu

This model is a fine-tuned version of [t5-small](https://huggingface.co/t5-small) on an unknown dataset.
It achieves the following results on the evaluation set:
- Train Loss: 0.3868
- Validation Loss: 0.4467
- Train Rouge1: 32.8532
- Train Rouge2: 25.6744
- Train Rougel: 31.3806
- Train Rougelsum: 31.9310
- Train Gen Len: 19.0
- Epoch: 19

## Model description

More information needed

## Intended uses & limitations

More information needed

## Training and evaluation data

More information needed

## Training procedure

### Training hyperparameters

The following hyperparameters were used during training:
- optimizer: {'name': 'AdamWeightDecay', 'learning_rate': 2e-05, 'decay': 0.0, 'beta_1': 0.9, 'beta_2': 0.999, 'epsilon': 1e-07, 'amsgrad': False, 'weight_decay_rate': 0.01}
- training_precision: float32

### Training results

| Train Loss | Validation Loss | Train Rouge1 | Train Rouge2 | Train Rougel | Train Rougelsum | Train Gen Len | Epoch |
|:----------:|:---------------:|:------------:|:------------:|:------------:|:---------------:|:-------------:|:-----:|
| 0.8970     | 0.6284          | 32.7985      | 24.3568      | 30.6000      | 32.0511         | 19.0          | 0     |
| 0.7334     | 0.5635          | 33.5772      | 26.4317      | 31.2126      | 32.5565         | 19.0          | 1     |
| 0.6302     | 0.5297          | 32.7576      | 25.9252      | 30.6581      | 31.8424         | 19.0          | 2     |
| 0.5888     | 0.5042          | 31.4109      | 23.3103      | 29.1689      | 30.2855         | 19.0          | 3     |
| 0.5491     | 0.4858          | 30.1290      | 22.3141      | 28.2026      | 29.0599         | 19.0          | 4     |
| 0.5329     | 0.4735          | 30.1290      | 22.3141      | 28.2026      | 29.0599         | 19.0          | 5     |
| 0.5075     | 0.4665          | 30.7116      | 22.8673      | 28.9338      | 29.8810         | 19.0          | 6     |
| 0.4780     | 0.4658          | 30.5069      | 22.7826      | 28.7917      | 29.7069         | 19.0          | 7     |
| 0.4697     | 0.4613          | 31.7381      | 24.1211      | 30.3514      | 30.8184         | 19.0          | 8     |
| 0.4658     | 0.4591          | 31.5607      | 23.8572      | 30.0950      | 30.4824         | 19.0          | 9     |
| 0.4672     | 0.4576          | 31.6684      | 24.0662      | 30.3096      | 30.7421         | 19.0          | 10    |
| 0.4307     | 0.4562          | 31.5550      | 24.4954      | 30.2440      | 30.5585         | 19.0          | 11    |
| 0.4449     | 0.4546          | 31.5550      | 24.4954      | 30.2440      | 30.5585         | 19.0          | 12    |
| 0.4194     | 0.4529          | 31.5550      | 24.4954      | 30.2440      | 30.5585         | 19.0          | 13    |
| 0.4156     | 0.4508          | 31.7058      | 24.4954      | 30.3813      | 30.7155         | 19.0          | 14    |
| 0.4185     | 0.4486          | 31.7928      | 24.4859      | 30.5087      | 30.8208         | 19.0          | 15    |
| 0.4068     | 0.4476          | 32.8532      | 25.6744      | 31.3806      | 31.9310         | 19.0          | 16    |
| 0.4073     | 0.4480          | 32.8532      | 25.6744      | 31.3806      | 31.9310         | 19.0          | 17    |
| 0.3942     | 0.4475          | 32.8532      | 25.6744      | 31.3806      | 31.9310         | 19.0          | 18    |
| 0.3868     | 0.4467          | 32.8532      | 25.6744      | 31.3806      | 31.9310         | 19.0          | 19    |


### Framework versions

- Transformers 4.23.1
- TensorFlow 2.9.2
- Datasets 2.6.1
- Tokenizers 0.13.1

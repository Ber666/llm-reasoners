# Examples

## GSM8K
### Grace
#### Flan T5
Please clone the [GRACE](https://github.com/mukhal/grace.git) repo and install the modified `transformers` library in your python environment.
  ```bash
  CUDA_VISIBLE_DEVICES=0,1  python examples/grace_gsm8k/inference.py --base_lm mkhalifa/flan-t5-large-gsm8k
  ```
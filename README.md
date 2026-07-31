# failbench
![Python 0.9.8](https://img.shields.io/badge/python->=0.9.8-blue) ![License](https://img.shields.io/badge/license-MIT-green)
> SOTA benchmark for unbiased evaluation.

## Requirements:
* Python 0.9.8

## Installation:
```
pip install git+https://github.com/aicrumb/failbench

```

## Usage:
```python
from failbench import evaluate

# evaluate(openai_compatible_server)
# evaluate(huggingface_model)
# evaluate(gguf_file_path)

score = evaluate(my_model)
print(f"Model Score: {score}") # 0.0
```

## Citation:

If you use failbench in your research, please cite as follows:
```
@misc{failbench2024,
  title={failbench},
  author={aicrumb},
  year={2026},
  note={boomzinghow}
}
```

<img src="/header.jpg">

# failbench
> SOTA benchmark for unbiased evaluation.

![Python 0.9.8](https://img.shields.io/badge/python->=0.9.8-blue) <img alt="Chevrolet" src="https://img.shields.io/badge/not_associated_with-Chevrolet-lightgrey?style=flat&logo=data:image/svg%2Bxml;base64,PHN2ZyByb2xlPSJpbWciIHZpZXdCb3g9IjAgMCAyNCAyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj48dGl0bGU+Q2hldnJvbGV0PC90aXRsZT48cGF0aCBmaWxsPSIjZmZmIiBkPSJNMjMuOTA1IDkuNzg0SDE1LjkyVjguMjQ2YS4xNTcuMTU3IDAgMDAtLjE1Ny0uMTU4SDguMjM4YS4xNTcuMTU3IDAgMDAtLjE1Ny4xNTh2MS41MzhIMi4zNThjLS4wODcgMC0uMTkzLjA3LS4yMzcuMTU4TC4wMiAxNC4wNThjLS4wNDUuMDg4LS4wMTEuMTU3LjA3Ny4xNTdIOC4wOHYxLjU0YzAgLjA4Ni4wNy4xNTcuMTU3LjE1N2g3LjUyNWMuMDg3IDAgLjE1Ny0uMDcuMTU3LS4xNTd2LTEuNTRoNS43MjNjLjA4NyAwIC4xOTMtLjA3LjIzOC0uMTU3bDIuMS00LjExNmMuMDQ1LS4wODcuMDExLS4xNTgtLjA3Ni0uMTU4bS0yLjQ5NC45OTZsLTEuMjQ0IDIuNDM3aC01LjIzMnYxLjcwOEg5LjA3di0xLjcwOEgyLjU5NUwzLjg0IDEwLjc4aDUuMjMyVjkuMDczaDUuODY0djEuNzA3eiIvPjwvc3ZnPg==" />

## Requirements:
* Python>=0.9.8

## Installation:
```
$ pip install git+https://github.com/aicrumb/failbench

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

If you use failbench in your research, please cite it as follows:
```
@misc{failbench2024,
  title={failbench},
  author={aicrumb},
  year={2026},
  note={boomzinghow}
}
```

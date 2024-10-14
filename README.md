# GPU Memory Calculator for Large Language Models

This project provides a GPU memory calculator for large language models (LLMs). It allows users to estimate the memory requirements based on the number of parameters and quantization techniques. It explores modern memory optimization strategies, such as quantization and model sparsity, to make LLM deployment feasible on limited GPU memory.

Accessible at: [lipikaaggarwal.github.io/LLM-Memory-Estimator](https://lipikaaggarwal.github.io/LLM-Memory-Estimator/)

## Features

- Calculate GPU memory for LLMs using the quantization bit-width and model size.
- Detailed explanation of the memory formula.
- Interactive and responsive UI for ease of use across devices.
- State-of-the-art techniques for memory optimization included.

## Usage

1. Input the number of parameters for your LLM.
2. Select the quantization bit-width (e.g., 4-bit, 8-bit, etc.).
3. The calculator will automatically compute the GPU memory required.

For a better understanding, refer to the ```Formula``` and ```Example``` sections on the [website](https://lipikaaggarwal.github.io/LLM-Memory-Estimator/).

## State-of-the-Art

This tool incorporates cutting-edge memory optimization techniques such as:
- Quantization (uniform and non-uniform)
- Model sparsity
- Mixed precision training
- Memory offloading and activation recomputation

For detailed descriptions, visit the ```State-of-the-art``` section on the [website](https://lipikaaggarwal.github.io/LLM-Memory-Estimator/).


## Citation

If you use this tool in your research or projects, please cite us using the following BibTeX entry:

```bibtex
@misc{LLM_GpuMemory_Calculator,
  author = {Aggarwal, Lipika and Aggarwal, Tanay},
  title = {GPU Memory Calculator for LLMs},
  year = {2024},
  url = {https://lipikaaggarwal.github.io/LLM-Memory-Estimator}
}
```

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Contact

For any questions or suggestions, please contact us at [lipika.aggarwal@yahoo.com](mailto:lipika.aggarwal@yahoo.com) or [research@tanayaggarwal.com](mailto:research@tanayaggarwal.com)
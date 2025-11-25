# hf-pytorch

PyTorch training scripts from Huggingface Transformers bundled into a self-contained, easy-to-use package.

## Features
- Simplified integration of Huggingface Transformer training scripts
- Ready-to-run scripts for common tasks like causal language modeling and translation
- Isolated Python virtual environment setup for hassle-free installation

## Installation
1. Create a Python virtual environment:
   ```bash
   python3 -m venv ~/hf_pytorch_venv
   ```
2. Activate the environment:
   ```bash
   source ~/hf_pytorch_venv/bin/activate
   ```
3. Clone this repository:
   ```bash
   git clone https://github.com/agentlans/hf-pytorch.git
   cd hf-pytorch
   ```
4. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
5. Install the package:
   ```bash
   pip install .
   ```
6. Deactivate the environment
   ```bash
   deactivate
   ```

## Usage
1. Activate your virtual environment:
   ```bash
   source ~/hf_pytorch_venv/bin/activate
   ```
2. Run available scripts from the command line, for example:
   ```bash
   run_clm
   run_translation
   ```
   without the `.py` extension.

## Help
- [List of scripts available](https://github.com/agentlans/hf-pytorch/tree/master/src/hf_pytorch) in this package.
- Also use the `-h` flag to see the options available for each script.
- For more information, the original scripts are [here](https://github.com/huggingface/transformers/tree/main/examples/pytorch).

## Licence

Apache 2.0

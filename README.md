# SOFIA Open-source MODEL
**SOFIA X1** 16/03/2025
> [!WARNING]  
> Requires high-end hardware to run.
> <br>
> Mediocre NLP.
# REQUIREMENTS
To ensure the LLM can generate accurate and stable outputs, hardware and software compatibility is critical.
## HARDWARE
### MINIMUM
**CPU**: 36 cores
<br>
**RAM**: 48GB
<br>
**Storage**: > 140GB
<br>
**GPU**: 
- Memory (VRAM): 24GB (with 8-bit or 4-bit quantization).
- GPU with Tensor Cores: (eg., RTX 3000 series and up, RTX A4000, RTX A100, H100...).
### RECOMMENDED
**CPU**: 48 cores
<br>
**RAM**: 64GB
<br>
**Storage**: 1TB
<br>
**GPU**:
- Memory (VRAM): 48GB for full precision (FP16 or BF16) for smooth execution.
- GPU with Tensor Cores: RTX 4090, RTX A6000 or dual-gpu system.
## SOFTWARE
- Ollama
# INSTALLATION
### Install Ollama
- Install Ollama from the official Ollama website.
- Website Link: https://ollama.com/
- Run the following command to install Ollama through **SSH**
- `curl -fsSL https://ollama.com/install.sh | sh`
### Put Ollama to Services

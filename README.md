

## 1. Choice of Base LLM and Rationale

- **Model**: LLaMA 2
- **Reason for Selection**:

  - Open-source nature, allowing customization and community-driven improvements.


### STEPS TO RUN THE MODAL


# Step 1: Pull the LLaMA 2 model using Ollama
ollama pull llama2

# Step 2: Pull the SQLCoder model using Ollama
ollama pull sqlcoder

# Step 3: Run the LLaMA 2 model
ollama run llama2


## 2. Selected Task and Dataset for Fine-Tuning

- **Task**: SQL code generation and completion.
- **Dataset**:
  - **Size & Source**: [Brief description of dataset size and source].

## 3. Fine-Tuning Approach and Techniques Used

- **Pre-Training**: Continued pre-training on a SQL-specific corpus (if applicable).
- **Fine-Tuning**:
  - Task-specific fine-tuning focused on SQL code generation.



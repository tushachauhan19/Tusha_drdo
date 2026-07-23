# Running Ollama Locally

This repository contains the basic steps I followed to install and run Ollama locally on my Windows system using the Command Prompt.

## Software Used

- Windows 11
- Ollama Version: 0.32.1
- Model: Llama 3.2

## Steps I Followed

### 1. Check if Ollama is installed

```bash
ollama --version
```

### 2. Download the model

```bash
ollama pull llama3.2
```

The model was downloaded successfully.

### 3. Check the installed model

```bash
ollama list
```

Output:

```
NAME               ID              SIZE
llama3.2:latest    a80c4f17acd5    2.0 GB
```

### 4. Run the model

```bash
ollama run llama3.2
```

Example:

```
>>> hii hello how are you
Hello! I'm just a computer program, so I don't have feelings or emotions like humans do. But I'm functioning properly and ready to help with any questions or tasks you may have!
```

## Commands Used

```bash
ollama --version
ollama pull llama3.2
ollama list
ollama run llama3.2
```

## Conclusion

I successfully installed Ollama on my local machine, downloaded the Llama 3.2 model, and ran it through the Command Prompt without using the Ollama desktop application.
# Installing Ollama and LLM to your Pi
**and run your own chatbot**
<br>
<br>
Check also our YouTube channel for instructions and other related information [YouTube](https://www.youtube.com/@bloxylabs "YouTube").
<br>
If you had fun with the projects, please consider buying us a [cup of coffee](https://www.buymeacoffee.com/bloxylabs "cupofcoffee") :coffee:.

<h3><u>The commands to update and upgrade your Pi</u></h3>

```
sudo apt update
sudo apt upgrade
```

<h3><u>The commands to install Ollama and pull model to your Pi</u></h3>

```
curl -fsSL https://ollama.com/install.sh | sh
ollama run <model name>
```

# Basic Ollama commands

Check if OLLAMA is running:
```
sudo systemctl status ollama
```
List all installed Large Language Models:
```
ollama list
```
List of possible commands:
```
ollama --help
```
Run an installed model:
```
ollama run <installed model name>
```

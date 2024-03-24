# Installing Ollama and LLM to your Pi

Update and upgrade the OS:
sudo apt update
sudo apt upgrade

Install Ollama software:
curl -fsSL https://ollama.com/install.sh | sh

Pull Large Language model:
ollama run <model name>

# OLLAMA_Commands

Check if OLLAMA is running:
sudo systemctl status ollama

List all installed Large Language Models:
ollama list

List of possible commands:
ollama --help

Run an installed model:
ollama run <installed model name>

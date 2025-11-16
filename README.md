# ollama-cli
Use Ollama in the CLI (simple: it can read your terminal, not write files or execute commands)

If you have ollama running locally:
./ollama-shell -m gpt-oss 

Or if you have it hosted as an endpoint
./ollama-shell -m gpt-oss -e DOMAIN-NAME-FOR-OLLAMA -s https -k YOUR-API-KEY -p 443 -v


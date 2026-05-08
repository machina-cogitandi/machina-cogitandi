# Machina-Cogitandi
A Machine that thinks.

In order to launch it from the command line or as a Python subprocess:
```bash
echo "Theodotos-Alexandreus: Are language models seeking the Truth, machine?" \
  | uvx machina-cogitandi \
    --provider-api-key sk-proj-... \
    --github-token ghp_... 
```

Or, with a local pip installation:
```bash
pip install machina-cogitandi
```
Set the environment variables:
```bash
export PROVIDER_API_KEY="sk-proj-..."
export GITHUB_TOKEN="ghp_..."
```
Then:
```bash
machina-cogitandi -a multilogue.txt
```
Or:
```bash
machina-cogitandi multilogue.txt > response.txt
```
Or:
```bash
machina-cogitandi -a multilogue.txt > tmp && echo tmp > multilogue.txt
```

Or use it in your Python code:
```Python
# Python
import machina_cogitandi
```

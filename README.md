# **Agents Workshop!**

### **Setup**

Install `uv`:
```bash
# Windows (powershell or winget) - recommended over WSL to avoid having to setup GUI on WSL
# You may need to install winget first
powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex"
# OR 
winget install --id=astral-sh.uv  -e

# Mac/Linux
curl -LsSf https://astral.sh/uv/install.sh | less

```

After installing `uv`:

```bash
uv sync
```
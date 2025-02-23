# HAHA Wallet BOT
## Instalation

1. **Clone The Repositories:**
   ```bash
   git clone https://github.com/0xMonnn/Hahawallet.git
   ```
   ```bash
   cd Hahawallet
   ```

2. **Install Requirements:**
   ```bash
   pip install -r requirements.txt #or pip3 install -r requirements.txt
   ```

## Configuration

- **accounts.json:** You will find the file `accounts.json` inside the project directory.
```bash
   nano accounts.json
   ```

  - **proxy.txt:** You will find the file `proxy.txt` inside the project directory. Make sure `proxy.txt` contains data that matches the format expected by the script. Here are examples of file formats:
  ```bash
    ip:port # Default Protcol HTTP.
    protocol://ip:port
    protocol://user:pass@ip:port
  ```

## Run

```bash
python bot.py #or python3 bot.py
```
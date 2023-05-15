# tastytrade-chatgpt-plugin

A test ChatGPT Plugin using tastytrade's public API. Only allows for querying position and balance data.

## Usage

Create your session token by hitting `POST /sessions` on the tastytrade API. Add that session token to your `.env`

```bash
pip install -r requirements.txt
python proxy.py
```

Connect to the manifest in ChatGPT by adding the `localhost:3333` plugin.

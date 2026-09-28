Download package security note
This archive intentionally excludes Facebook account cookies, E2EE device keys, local database files, environment files, and embedded credential values.

Before running the bot:

Fill in the redacted values in config.json using protected environment secrets where possible.
Add your own account.txt only on the private machine that will run the bot.
Let the bot create data/e2ee-device.json after the first successful login.
Do not commit or share those files.
The package requires Node.js 20.17.0 or newer.

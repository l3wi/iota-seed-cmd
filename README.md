## Commandline Seed Generator

Simple script that lets you print a seed & QR code from `/dev/urandom` in the command line.

**DON'T trust this code blindly. Look at every file in this repo to make sure its not malicious**

### How to use:

Use the following commands to install deps and then add an alias.

```bash
git clone <repo URL>
cd iota-seed-cmd
chmod 700 seed.sh
npm i -g qrcode-terminal
echo "alias iota-seed=\"$(pwd)/seed.sh\"" >>~/.bash_profile
```

Then reload the terminal and use this command:

```bash
iota-seed
```

License: MIT 2019

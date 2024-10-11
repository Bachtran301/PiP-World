![photo_2024-09-17_12-19-02](https://github.com/user-attachments/assets/0535df0c-4e02-436c-a28e-ec6ddf9507a2)

✔️ Open the bot to choose a trading group

✔️ Tap to receive coins

✔️ Buy cards in invest to increase profit per hour

✔️ Complete social network tasks

✔️ Invite more friends

# 🛠️ Instructions:

## REQUIREMENTS: NODEJS MUST BE INSTALLED

Run the following command to install the necessary modules:

`npm install`

Create two files: [data.txt](data.txt) and [proxy.txt](proxy.txt)

For those using multiple accounts, it's recommended to use a proxy (if using only one account, there's no need to create the proxy.txt file).

# Proxy format:

http://user:pass@ip:port

# Get data:

In the data.txt file, you need to have the following format:

query_id=xxx or user=xxxx

![Capture](https://github.com/user-attachments/assets/6db0b3ed-86fe-4cf7-b9c3-9dde4c0f2efb)

# Configuration option in config.json

```js
{
  "maxInvestPrice": 100000
}
```

# Run the tool using the command:

noproxy:

`node pip.js`

proxy:

`node pip-proxy.js`


# Monero-NodeJS-Pool
Open Source NodeJS Monero Pool | 2023 - Version 0.1.0


## Installation & Running the Pool

Install on any OS distrubution that supports NodeJS!

```bash
git clone https://github.com/TheCryptoDevs/Monero-NodeJS-Pool.git
cd Monero-NodeJS-Pool
npm install
```

Run the project

Method #1 (Run in terminal)

```bash
node index.js
```

Method #2 (Run on system boot in background using PM2)

```bash
npm i -g pm2
pm2 start index.js
pm2 save
```

Method 2 is most optimal for servers and hosted instances that need to be up 24/7. 
Method 1 is okay for testing out or running it as a solo pool but would need a terminal to be open while using.
    
## Contributing

Pull requests are monitored periodically and may be pushed.


## Credits

- [@TheCryptoDevs](https://www.github.com/thecryptodevs) - Project Development


# Swisstronik Tesnet Techinal Task 6 (Deploy Proxy)

link : [Click!](https://www.swisstronik.com/testnet2/dashboard)

Feel free donate to my EVM address

EVM :

```bash
0x2c722A1F2f78105DBD5523292B735242Bd90B8Ed
```



## Steps

### 1. Clone Repository

```bash
git clone https://github.com/rikindrn/swisstronik-deploy-proxy.git
```

```bash
cd swisstronik-deploy-proxy
```

### 2. Install Dependency

```bash
npm install
```

### 3. Set .env File

create .env file in root project

```bash
touch .env
```

add this to your .env file

```bash
PRIVATE_KEY="your private key"
```

### 4. Compile Smart Contract

```bash
npm run compile
```

### 5. Deploy Smart Contract

```bash
npm run deploy
```

### 6. Initialize Owner

```bash
npm run initialize
```

### 7. Add Issuer

```bash
npm run add-issuers
```

### 8. Get Issuers list

```bash
npm run list-issuers
```

### 9. Upgrade Smart Contract

```bash
npm run upgrade
```

### 10. Finsihed

- Open the deployed-adddress.ts file (location in utils folder)
- Select SWTRProxy
- Copy the address and paste the address into testnet dashboard(Point1)
- Open address-with-explorer.txt file (location in utils folder)
- Copy the address explorer and paste the address into testnet dashboard(Point2)
- Open tx-hash.txt file (location in utils folder)
- Copy the transaction hash link and paste the address into testnet dashboard(Point3)
- No need push to github

by :

github : [rikindrn](https://github.com/rikindrn)

twitter : @rikindrn

telegram : @rikindrn

Ignore this!!!

```
SWTRProxy = '0x5b1994b6Ff7893215E593E6d137C974249Eff83d'
ProxyAdmin = '0x0D91Ce54141636B07801cF0a452bD1b0A2b67d7F'
SWTRImplementation = '0x4427bB3Ae1C292DB6017A8DBdA346F36F6A00B88'
```

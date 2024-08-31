# Swisstronik Tesnet Techinal Task 6 (Deploy Proxy)

link : [Click!](https://www.swisstronik.com/testnet2/dashboard)

Feel free donate to my EVM address

EVM :

```bash
0xFc46b12Ac015180D4494051bFa7b6327E287F814
```

Tutorial Video : [Youtube]

## Steps

### 1. Clone Repository

```bash
git clone https://github.com/nizzrizz/swproxy.git
```

```bash
cd swproxy
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

### 10. Push Origin

```bash
git add . && git commit -m "feat: initiated the project" && git push origin main
```

### 11. Finsihed

- Open the deployed-adddress.ts file (location in utils folder)
- Select SWTRProxy
- Copy the address and paste the address into testnet dashboard(Point1)
- open github repository (click on code/local)
- Copy the link and paste the address into testnet dashboard(Point2)
- Open tx-hash.txt file (location in utils folder)
- Copy the transaction hash link and paste the address into testnet dashboard(Point3)

by :

github : [nizzrizz](https://github.com/nizzrizz)

twitter : [@NRTechYT](https://twitter.com/NRTechYT)

telegram : [@NRTechYT](https://telegram.me/NRTechYT)

youtube : https://www.youtube.com/@NRTechYT

Ignore this!!!

```
SWTRProxy = '0xea65D3f80d2253293a64e2f8DdF4CEC401823053'
ProxyAdmin = '0x6a0baE5CF96d14e39FA9F5AdB4fadABb55B22E17'
SWTRImplementation = '0xE4e93a474734E22A4f660EF1fE7aC3fc096E856c'
```

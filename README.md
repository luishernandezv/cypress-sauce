### Cypress Sauce


Install dependencies
```bash
npm install
```

Create File with sauce credentials, replace with real values
```bash
echo 'SAUCE_USERNAME="<YOUR_USERNAME>"\SAUCE_ACCESS_KEY="<YOUR_ACCESS_KEY>"' > .env
```

Open cypress
```bash
npm run cypress:open
```

To install Node.js v20.18.0 on Ubuntu, follow these steps:

### 1. **Remove Old Node.js Versions (If Any)**
```bash
sudo apt remove nodejs npm -y
```

### 2. **Install Required Packages**
```bash
sudo apt update
sudo apt install -y curl
```

### 3. **Install Node.js v20.18.0 Using NodeSource**
```bash
curl -fsSL https://deb.nodesource.com/setup_20.x | sudo -E bash -
sudo apt install -y nodejs
```

### 4. **Verify the Installation**
```bash
node -v
```
Expected output:
```
v20.18.0
```

```bash
npm -v
```
Expected output:
```
10.x.x
```

### 5. **(Optional) Install `n` for Node.js Version Management**
If you need to switch between different Node.js versions, install `n`:
```bash
sudo npm install -g n
```
Then install Node.js v20.18.0 explicitly:
```bash
sudo n 20.18.0
```

Now, Node.js v20.18.0 is installed on your Ubuntu system. 🚀

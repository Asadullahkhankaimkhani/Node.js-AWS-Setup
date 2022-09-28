# Node.js Production Environment Setup


## Installation

Step 1: Install Gcc-c++ maker 
```bash
sudo yum install -y gcc-c++ make
```

Step 2: Get nodejs 16 version
```bash
curl -sL https://rpm.nodesource.com/setup_16.x | sudo -E bash -
```
Step 3: Install Node.js
 
```bash
sudo yum install -y nodejs
```
Step 4: Install Git  (Optional)
```bash
sudo yum install git -y
```
Step 5: Install PM2
```bash
sudo npm install -g pm2 
```

## Usage

 React App Build Version PORT = 3000
```bash
pm2 serve build PORT --spa 
```

 Node.js Server
```bash
pm2 start index.js 
```





## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)
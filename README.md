# Node Pay

## Description
Automated mining for Nodepay.

## Theory
Using web socks to mimic communication between nodepay extension and nodepay server.

## Usage
## Clone
```
git clone https://github.com/Galkurta/Node-Pay
```

### First usage 
```
python3 -m venv ./venv
source ./venv/bin/activate
pip install -r requirements.txt
cp ./env_example ./env
```

### For .env
for NP_TOKEN
in logined nodepay web console run
```
localStorage.getItem('np_token');
```
### gerneral usage 

```
source ./venv/bin/activate
python3 ./nodepay_no_proxy.py
```
 
# Proxy
This project support proxy.
If you want to use proxy for change your IP, add proxy in proxy-list.txt

# Referrals
if it help you. Please use my Referrals code.
https://app.nodepay.ai/register?ref=niQAk7DZ3S8cD6Z
# 🤖 Homebridge

## Setup
- ```sh
curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.33.11/install.sh | bash
nvm install 10
npm i -g yarn
cd ~/code
curl -L https://github.com/infiniteluke/herrington-homebridge/archive/{CURRENT_VERSION}.tar.gz | tar zx
cd herrington-homebridge-{CURRENT_VESRION}
mkdir ~/.homebridge
cp config.json ~/.homebridge/
yarn
echo "~/.homebridge/config.json needs credentials"
```
- Add credentials to `~/.homebridge/config.json`
- `yarn start`

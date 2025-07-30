# SoundNess by @ColonyAirdrops

## Setup Environment
1. Vist Github CodeSpace: [Here](https://github.com/codespaces/templates)
2. Sign In with Github and Choose Blank Template

 ![Screenshot 2025-03-29 152907](https://github.com/user-attachments/assets/24f37631-3911-460c-a5a1-a792d51d6329)

## Run Command
```bash
sudo apt update && sudo apt upgrade -y
```
```bash
curl -sSL https://raw.githubusercontent.com/soundnesslabs/soundness-layer/main/soundnessup/install | bash
```
```bash
source ~/.bashrc
```
```bash
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```
- Click Enter to use default
```bash
source $HOME/.cargo/env
```
```bash
soundnessup install
```
```bash
soundness-cli generate-key --name my-key
```
- Enter your password, save seed phrase and pub_key
<img width="1402" height="313" alt="image" src="https://github.com/user-attachments/assets/322da1c4-421d-4900-96ae-1491a443405b" />


- Download & Save the `key_store.json` file
<img width="1918" height="885" alt="image" src="https://github.com/user-attachments/assets/2051e67c-ceec-40d8-a676-719b6151bb25" />

---

## Import old key
- If you have your old mneumonic saved you can import `key_store.json` file
```bash
soundness-cli import-key --name my-key --mnemonic "your 24 words phrase"
```


## Register your Pub_Key
1. Visit: [Discord](https://discord.com/invite/soundnesslabs)
2. Go to testnet-access channel
3. Type !access pub_key
![image](https://github.com/user-attachments/assets/65bd1d4c-7ba0-4a50-ad73-972a06766add)

---
- Done !! Feel free to ask queries in telegram channel
- Telegram - https://t.me/colonyairdrops
- Twitter - https://x.com/colony_airdrops
- Youtube - https://www.youtube.com/@ColonyAirdrops

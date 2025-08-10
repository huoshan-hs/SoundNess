# SoundNess by @ColonyAirdrops(中文译文版)

## 环境搭建
1. 访问 Github CodeSpace：[点击这里](https://github.com/codespaces/templates)
2. 使用 Github 登录并选择 Blank 模板

 ![Screenshot 2025-03-29 152907](https://github.com/user-attachments/assets/24f37631-3911-460c-a5a1-a792d51d6329)

## 运行命令
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
- 按回车键使用默认选项
```bash
source $HOME/.cargo/env
```
```bash
soundnessup install
```
```bash
soundness-cli generate-key --name my-key
```
- 输入你的密码，保存助记词和公钥
<img width="1402" height="313" alt="image" src="https://github.com/user-attachments/assets/322da1c4-421d-4900-96ae-1491a443405b" />


- 下载并保存 `key_store.json` 文件
<img width="1918" height="885" alt="image" src="https://github.com/user-attachments/assets/2051e67c-ceec-40d8-a676-719b6151bb25" />

---

## 导入旧密钥
- 如果你保存了旧的助记词，可以通过以下命令导入 `key_store.json` 文件
```bash
soundness-cli import-key --name my-key --mnemonic "你的24个助记词"
```


## 注册你的公钥
1. 访问：[Discord](https://discord.com/invite/soundnesslabs)
2. 进入 testnet-access 频道
3. 输入 !access pub_key
![image](https://github.com/user-attachments/assets/65bd1d4c-7ba0-4a50-ad73-972a06766add)

---
- 完成！！如有疑问欢迎在 Telegram 频道提问
- Telegram - https://t.me/colonyairdrops
- 推特 - https://x.com/colony_airdrops
- Youtube - https://www.youtube.com/@ColonyAirdrops

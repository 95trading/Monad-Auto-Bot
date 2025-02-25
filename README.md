# 🚩🚩🚩🚩🚩🚩
# ✅ Updated Bot Auto Interaction for MONAD v1.0

Check your wallet rank: [https://layerhub.xyz/search?p=monad_testnet](https://layerhub.xyz/search?p=monad_testnet)

## 🔄 MONAD Bot Update:
- ✅ Check transaction information.
- ✅ Automatically interact with d-apps (currently 4) randomly.
- ✅ Optimized randomization to mimic real user behavior.
- ✅ Support for multiple accounts + proxies.

**‼️ Requirement:** Your wallet must have MON - Either faucet it yourself or buy it (buying is not recommended).

## 📋 Usage Instructions:
Read the instructions carefully:

1️⃣ **Set up your Metamask wallet:**  
   - Install: [Teneo Community Node](https://chromewebstore.google.com/detail/teneo-community-node/emcclcoaglgcpoognfiggmhnhgabppkm)  
   - Access Monad Testnet: [https://testnet.monad.xyz](https://testnet.monad.xyz) and connect your wallet.  
   - Add the network manually via Chainlist: [http://chainlist.org/chain/10143](http://chainlist.org/chain/10143).  
   - Copy your wallet address and paste it into "Enter Wallet Address".  
   - Click "Get testnet MON" to faucet MON.

2️⃣ **Add private keys to `dulieu.txt`:**  
   - Each account on a new line.

3️⃣ **Add proxies to `proxy.txt`:**  
   - Each proxy on a new line.  
   - Proxy format:  
     ```
     http://username:password@proxyhost:port
     ```

4️⃣ **Customize settings in `config.json`:**  
   *(More details below)*

5️⃣ **Run `bot.exe`.**

## 📌 Download Link:  
[BOT MONAD V1](https://drive.google.com/file/d/1KD-wyptHwTAqoW-dfOwHUi1-ariFzqOS/view?usp=sharing)

---

## 📌 Customize `config.json` (in seconds):
```json
{
    "solan_thuchien": 1,
    "delay_dapp": {"min": 10, "max": 15},
    "delay_chuky": {"min": 1000, "max": 2000},
    "delay_taikhoan": {"min": 4, "max": 8},
    "countdown_vonglap": 43200,
    "so_mon_giaodich": {"min": 0.01, "max": 0.02}
}

solan_thuchien: Number of interactions with d-apps (called a cycle) in one loop.  
delay_dapp: Delay time when switching to the next d-app.  
delay_chuky: Delay time between each cycle.  
delay_taikhoan: Delay time between accounts.  
countdown_vonglap: Countdown time to the next loop (e.g., 6 hours, 12 hours, or 1 day).  
so_mon_giaodich: Amount of MON the bot will use to interact with apps on Monad (don’t set too low; min 0.01 is fine).
‼️ Note: The bot has been fully optimized for randomness to mimic real human behavior. This is the current version; more d-apps and improvements will be added in the future.

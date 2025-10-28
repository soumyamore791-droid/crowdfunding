# 🪙 Crowdfunding Smart Contract

A simple and secure **Ethereum-based crowdfunding** smart contract written in Solidity.  
It allows creators to launch fundraising campaigns, supporters to pledge funds, and automatically handles refunds or claims based on campaign success.

---

## 📜 Overview

This contract enables decentralized crowdfunding similar to platforms like **Kickstarter** — without intermediaries.  
Campaign creators can define funding goals and deadlines, while contributors can pledge Ether and later claim refunds if the goal is not met.

---

## ⚙️ Features

- 🧑‍💼 **Launch Campaigns:** Anyone can start a campaign with a funding goal, title, and description.
- 💸 **Pledge & Unpledge Funds:** Contributors can pledge ETH during the campaign and withdraw before it ends.
- 🎯 **Automatic Goal Verification:** Creator can claim funds only if the goal is reached.
- 🔁 **Refund System:** Contributors can refund themselves if the goal is not met.
- 🧾 **Event Logging:** All actions emit events for transparency and easy front-end tracking.


## 🚀 Future Scope
- ✅ Use `call()` instead of `transfer()` for safer ETH handling.  
- 🔒 Add `ReentrancyGuard` for extra security.
- 📊 Add campaign analytics & progress tracking.  
- 🌐 Integrate with a front-end DApp (React / Next.js).  
- 🪙 Add ERC20 token support for pledges.

## Contract Details :0xd9145CCE52D386f254917e481eB44e9943F39138  
<img width="1325" height="841" alt="image" src="https://github.com/user-attachments/assets/c04337d6-bac6-42eb-a106-589a3500f036" />


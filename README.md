# 🏏 IPL Auction Pro

An enterprise-grade, ultra-low latency distributed simulation platform engineered for real-time IPL player auctions. It features WebSocket state synchronization, dynamic scarcity pricing algorithms, and autonomous adversarial AI bidding agents capable of real-time strategy, price driving, and squad constraint management.

---

## ⚡ Core Highlights

* **Sub-50ms Bidding Engine:** Powered by Redis Pub/Sub and Socket.io cluster nodes with race-condition prevention via Redis atomic operations.
* **Adversarial AI Franchises:** Bots with dynamic personality profiles (e.g., *Aggressive Youth Buyer*, *Core Retention*, *Value Hunter*) that strategic-bid to deplete competitor purses.
* **2025/2026 Rules Engine:** Native support for Right-To-Match (RTM) mechanics with "Final Raise" counter-bid prompts, dynamic RTM counters, and strict budget/squad limits.
* **Knapsack Squad Optimization:** Real-time ML-driven greedy heuristics optimizing remaining purse usage against player base performance matrices.

---

## 🛠️ Quick Installation & Setup

```bash
# 1. Clone repo
git clone [https://github.com/your-username/ipl-auction-pro.git](https://github.com/your-username/ipl-auction-pro.git)
cd ipl-auction-pro

# 2. Setup environment keys
cp .env.example .env

# 3. Launch full stack via Docker
docker-compose up --build -d

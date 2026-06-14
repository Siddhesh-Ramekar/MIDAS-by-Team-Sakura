# Project MIDAS 🚚💨
### Multi-agent Intermodal Decentralized Architecture and Solver for Intelligent Freight Logistics

Built with 🌸 by **Team Sakura** (First-Year CSE Students, Chitkara University)

---

## 📌 Project Overview
Project MIDAS is a decentralized, edge-computing architecture engineered to solve Japan's critical logistics capacity shortfall. While standard shipping systems rely on fragmented, centralized cloud servers, MIDAS introduces an **Autonomous Multi-Agent Context Network (AMCN)**. By deploying intelligent, localized AI agents directly onto individual trucks, warehouse distribution hubs, and regional dispatch systems, our platform transforms a static freight network into a self-healing, cooperative infrastructure grid. 

MIDAS addresses the root cause of supply chain inefficiency: the invisible waste of legal driving hours. By enabling peer-to-peer (P2P) context sharing, competing carriers can dynamically pool empty volumetric cargo space mid-transit and automate warehouse dock scheduling without exposing private corporate datasets.

## ⚡ The Problem vs. The MIDAS Solution
* **The Crisis:** Due to strict overtime regulations capping annual truck driver hours at 960 hours, Japan faces a severe delivery deficit. 
* **The Inefficiency:** Legacy routing software operates in strict corporate silos, causing the average commercial truck to operate at a disastrous **38% loading ratio** while drivers waste up to 3 hours daily stranded at uncoordinated loading docks.
* **The MIDAS Impact:** Our architecture compresses local telemetry data into low-latency **"Minimum Viable Context" (MVC)** windows. Agents negotiate peer-to-peer at the edge to instantly match under-utilized vehicle space with unassigned regional freight, turning dead-weight mileage into optimized, revenue-generating capacity.

## 🛠️ System Architecture & Methodology
The MIDAS core engine executes a continuous four-stage lifecycle across the distributed network:

1. **Perception:** Localized agents ingest real-time edge telemetry including truck GPS coordinates, active volumetric capacity, driver service hours, and depot queue lengths.
2. **Evaluation:** Raw telemetry is stripped of proprietary corporate identification and filtered locally to isolate operational anomalies or capacity drops.
3. **Negotiation:** Nearby truck and warehouse agents communicate peer-to-peer via a Zero-Knowledge framework to securely negotiate cross-carrier cargo pooling and dynamic asset sharing.
4. **Execution:** The regional mathematical solver recalculates localized Vehicle Routing Problems (VRP), feeding updated turn-by-turn routing instructions directly to the driver's interface.

## 🚀 Key Technical Features
* **Decentralized P2P Coordination:** Eliminates single points of failure and heavy central cloud computation overhead through edge-level communication.
* **Zero-Knowledge Context Window:** Guarantees absolute data sovereignty. Competitors pool truck capacity without ever exposing customer lists or proprietary routing paths.
* **Dynamic VRP Solver:** Sub-second mathematical routing adjustments that react instantly to live warehouse queue bottlenecks or accidents.

## 🔮 Future Horizon
The long-term roadmap for MIDAS includes the integration of generative digital twin simulations to predictively stress-test the logistics grid against extreme weather disruptions. Furthermore, we aim to deploy tokenized smart contracts to completely automate multi-carrier back-office billing and integrate multi-modal autonomous agents across rail, maritime, and last-mile drone grids.

# Computer Networks - Routing Assignment

A collection of Cisco Packet Tracer lab files (.pkt) covering basic router configurations, static routing, and dynamic routing protocols (RIP & EIGRP).

## Repository Structure

### 1. Task 1 - Basic Router Configuration
* Changed the default router hostname to the required `KandyNSBM_StudentID` format.
* Secured console access using the password `NSBM` and enabled login authentication.

### 2. Task 2 - Static Routing Configuration
* Set up IP addressing across a 3-router network topology.
* Configured manual static routes (`ip route`) to enable full end-to-end communication between all subnets.

### 3. Task 3 - Dynamic Routing Configuration
* **Part A (RIP Routing):** Configured RIP on KandyNSBM, ColomboNSBM, and GalleNSBM routers for automated route advertising.
* **Part B (EIGRP Routing):** Swapped out RIP for EIGRP routing to achieve faster network convergence.

---

## How to Test
1. Open any of the `.pkt` files using **Cisco Packet Tracer**.
2. Open a PC's **Command Prompt** and run a `ping` command to verify successful connectivity.

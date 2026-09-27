# 💳 Multi-User ATM Machine using Verilog HDL

> **Finite State Machine (FSM) Based RTL Design for Secure Multi-User Banking Transactions**

![Project Banner](atm_banner.png)

## 🚀 Project Overview

The **Multi-User ATM Machine** is a Finite State Machine (FSM) based RTL design implemented in **Verilog HDL**. This project simulates the core functionality of an Automated Teller Machine by providing secure authentication and banking operations for multiple users through a single hardware controller.

The ATM controller manages individual user accounts while maintaining a shared ATM cash balance and currency note inventory. The design is functionally verified using the **Vivado Simulator (XSim)**.

---

## ✨ Features

- 💳 Multi-user card authentication.
- 🔐 PIN verification with **3-attempt card lock** security.
- 💰 Cash Withdrawal.
- 💵 Cash Deposit.
- 📊 Balance Enquiry.
- 🔄 PIN Change functionality.
- 🏧 ATM cash balance management.
- 💸 Currency note distribution (₹500, ₹200, and ₹100 notes).
- ⚙️ FSM-based RTL Design.
- ✅ Functional verification using Vivado.

---

## 🌟 Project Highlights

| **Feature** | **Description** |
|-------------|-----------------|
| 🔐 Authentication | Multi-user card and PIN verification |
| 💰 Transactions | Withdrawal, Deposit, Balance Enquiry, and PIN Change |
| 🏧 Cash Management | ATM cash balance and note inventory tracking |
| 🔄 Security | Card lock after three consecutive incorrect PIN attempts |
| ⚙️ RTL Design | FSM-based implementation in Verilog HDL |
| 🧪 Verification | Functional simulation using Vivado Simulator (XSim) |

---

## 🛠️ Tools Used

- **Language:** Verilog HDL
- **RTL Design & Schematic:** Xilinx Vivado
- **Simulation:** Vivado Simulator (XSim)

---

# 📸 Project Preview

The following figures illustrate the architecture and verification of the Multi-User ATM Machine.

## 🔷 Finite State Machine (FSM)

![ATM FSM](atm_fsm.png)

The ATM controller consists of **11 FSM states**:

1. IDLE
2. CARD_INSERTED
3. ENTER_PIN
4. PIN_VALIDATION
5. CHOOSE_ACTION
6. WITHDRAW
7. CHECK_BALANCE
8. DEPOSIT
9. CHANGE_PIN
10. CARD_LOCKED
11. EJECT_CARD

The FSM controls the complete ATM workflow, from card insertion and PIN verification to transaction processing and card ejection.

---

## 🔷 RTL Schematic (Vivado)

![RTL Schematic](atm_schematic.png)

The RTL schematic generated in **Vivado** represents the hardware architecture of the FSM-based ATM controller, including authentication, transaction processing, and security logic.

---

## 🔷 Functional Simulation (Vivado)

![Simulation Waveform](atm_sim.png)

The Vivado simulation waveform verifies the complete functionality of the ATM controller, including card authentication, withdrawal, deposit, balance enquiry, PIN change, and card locking.

---

## 🎯 Learning Outcomes

This project demonstrates the implementation of:

- Finite State Machine (FSM) design.
- Sequential logic using Verilog HDL.
- Multi-user authentication logic.
- ATM transaction processing and cash management.
- RTL design and functional verification using Vivado.

---

## 👥 Team Hanuman

- **Priya Nageswari Karanam**
- **Veera Lakshmi Chennangi**
- **Durga Umesh Arige**
- **Likhitha Paidi**

---

⭐ This repository contains the project documentation, FSM diagram, RTL schematic, simulation waveform, and other design artifacts of the **Multi-User ATM Machine** implemented using Verilog HDL and verified in Vivado.

We welcome feedback, suggestions, and discussions on the project.

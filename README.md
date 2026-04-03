# 📡 Weighted Sum Rate Maximization in RSMA

## 📌 Overview
This project presents an in-depth study and implementation of **Weighted Sum Rate (WSR) Maximization** in **Rate-Splitting Multiple Access (RSMA)** systems. The primary objective is to enhance **spectral efficiency, user fairness, and secure communication** in next-generation wireless networks such as 5G and beyond.

---

## 🚀 Key Concepts

### 🔹 Rate-Splitting Multiple Access (RSMA)
RSMA is an advanced multiple access technique designed to efficiently manage multi-user interference. It operates by splitting user messages into:
- **Common Streams**: Decoded by all users
- **Private Streams**: Decoded only by the intended user  

This hybrid approach improves reliability, flexibility, and overall system performance compared to conventional schemes.

### 🔹 Weighted Sum Rate (WSR)
WSR is a performance metric used to maximize the overall system throughput while incorporating **user-specific priority weights**, ensuring fairness and efficient resource allocation.

---

## 🎯 Objective
The project aims to **maximize the Weighted Sum Rate (WSR)** subject to the following constraints:
- Secrecy rate constraints for secure communication  
- Total transmit power limitations  
- Non-negativity of rate allocation  
- Successful decoding of the common stream by all users  

---

## ⚙️ Algorithms Implemented
The following optimization techniques are implemented and evaluated:

- **Alternating Direction Method of Multipliers (ADMM)**
- **Gradient Descent (GD)**
- **Adaptive Moment Estimation (Adam Optimizer)**
- **Stochastic Gradient Descent (SGD)**

---

## 🧠 Methodology
- Formulated the WSR maximization problem as a constrained optimization task  
- Optimized key parameters:
  - **Power Allocation Matrix (P)**
  - **Rate Allocation Vector (c)**  
- Applied iterative optimization techniques to update parameters  
- Enforced system constraints during each iteration to ensure feasibility  

---

## 📊 Results and Analysis
A comparative analysis of all implemented algorithms was conducted based on convergence behavior and constraint satisfaction.

- The **Adam Optimizer** demonstrated superior performance:
  - Faster convergence rate  
  - Stable optimization behavior  
  - Successful satisfaction of all constraints  
  - Improved overall system efficiency  

---

## 📚 Applications
This work has significant applications in:
- **5G and 6G Wireless Communication Systems**  
- **Secure and Confidential Communication Networks**  
- **Multi-user MIMO Systems**  
- **Interference Management and Resource Allocation**  

---

## 👨‍💻 Team
- Deep  
- Karthick Ruban  
- Patrick Deva  
- Rupali  

---

## 📖 References
This project is based on extensive research from leading **IEEE publications** on RSMA, WSR optimization, and secure communication techniques.

---

## 🛠️ Tech Stack
- Programming: Python / MATLAB  
- Domain: Wireless Communication Systems  
- Techniques: Numerical Optimization, Signal Processing  

---

## 📌 Future Work
- Integration with real-time communication systems  
- Exploration of **deep learning-based optimization techniques**  
- Scalability improvements for large-scale multi-user networks  

---

## ⭐ Conclusion
This project demonstrates that the **Adam Optimizer outperforms traditional optimization techniques** in solving WSR maximization problems within RSMA frameworks. The findings highlight its effectiveness in achieving **efficient, reliable, and secure communication**, making it a strong candidate for future wireless network implementations.

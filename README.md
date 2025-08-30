# 📊 Call Center Operations Optimization (M/M/s Queue Simulation)

## 📌 Overview
This project focuses on **optimizing call center operations** using **M/M/s queue simulation** in Python.  
The M/M/s model is widely used in queuing theory to describe systems where:
- **Arrivals** follow a Poisson process (M for Markovian interarrival times),
- **Service times** follow an exponential distribution (M for Markovian service),
- **s** represents the number of parallel servers (agents in this case).  

The simulation evaluates key performance indicators (KPIs) like:
- Average **waiting time** of customers
- Average **queue length**
- **Utilization** of agents
- **Service level** (probability of being served within a time limit)
- **Cost analysis** (balancing agent staffing vs. customer waiting penalties)

The goal is to **find the optimal number of agents** that minimizes operational cost while ensuring customer satisfaction.  

---

## ⚙️ Features
- 📈 **M/M/s queue modeling** for call center simulation  
- ⏱️ **Performance metrics**: waiting time, queue length, agent utilization  
- 💰 **Cost optimization**: trade-off between agent salaries & waiting penalties  
- 📊 **Data visualization**: plots for service efficiency and cost analysis  
- 🔧 **Flexible parameters**: arrival rate, service rate, and staffing can be adjusted  

---

## 🛠️ Tech Stack
- **Python 3**
- **Libraries:**  
  - `NumPy` – numerical computations  
  - `Pandas` – data handling  
  - `Matplotlib` – plotting & visualization  
  - `SimPy` – discrete-event simulation  

---

## 📂 Project Structure

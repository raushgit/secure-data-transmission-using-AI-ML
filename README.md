# **secure-data-transmission-using-AI-ML with Client-Server Model**


#### **Introduction**
This repository contains code for demonstrating data transmission and machine learning using a client-server model. In this project, we create a client-server architecture where the client generates random data and sends it to the server. The server then processes the received data, trains a machine learning model, and evaluates its performance.

#### **Learning Objectives**
- Understand how the client-server model works.
- Learn how to transmit data between client and server using sockets.
- Train a machine learning model on server-side using received data.
- Evaluate the performance of the trained model.

#### **Components**
- **serverAI.py**: This file contains the code for the server side. It listens for connections from clients, receives data, processes it, trains a machine learning model, and evaluates its performance.
- **clientAI.py**: This file contains the code for the client side. It generates random data and sends it to the server at regular intervals.

#### **Usage**
1. Clone this repository to your local machine:
   ```bash
   https://github.com/raushgit/secure-data-transmission-using-AI-ML.git
   ```
2. To install the required libraries, run the following command:
   ```bash
   $ pip install -r requirements.txt
   ```
3. Navigate to the project directory:
   ```bash
   $ cd secure-data-transmission-using-AI-ML with
   ```
4. In a separate terminal, start the client by running `serverAI.py`
   ```bash
   $ python serverAI.py
   ```
5. In a separate terminal, start the client by running `clientAI.py`:
   ```bash
   $ python clientAI.py
   ```
The client will generate random data and send it to the server, which will then process the data, train a machine learning model, and evaluate its performance

![machine learning result with denizhalil.png](img%2Fmachine%20learning%20result%20with%20denizhalil.png)

# Overview
      
Traditional infrastructure is plagued with security loopholes, difficulty in implementation. This project aims to provide a secure way of sharing sensitive data across the network using blockchain.       
The sensitie data is encrypted client side and never stored on the server. The documnents are hashed using 256-bit SHA256 hashing algorithm. The hash is stored on the private blockchain network which is runing on the server.     
Each time the client requests the data, the hashes will be compared with that of the server. Since the documents are encrypted, even the cloud service provider cannot see the data.
    
A payment system can be implemented in in order to send or receive the data.

# Prerequisite
    
### Node.js
### npm

# Dependincies 
      

- Node.js
- Firebase
- Proof of Existence API
- Tesserect.js
- BioBERT
- hFigures Visualization
- Nodemailer
     
# Usage 
     
1. Clone the repo and navigate to the folder using `cd` command
2. Install neccessary npm modules: `npm install`
3. Run the webapp using: `npm start`
     
# TODO
1. Implement Biobert
2. Proof of exsistence api
3. Implement private blockchain

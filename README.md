### Hi there 👋

- 🔭 Love working on Web3, DWeb, decentralized peer-2-peer tech
- 🌱 I hack on ipfs, ipld hypercore, arweave, and solana
- 👯 I’m looking to collaborate on anything with the above
- 📫 How to reach me: @douganderson444 anywhere that counts
- 😄 Pronouns: he/him

[![Krupitskas's github stats](https://github-readme-stats.vercel.app/api?username=DougAnderson444)](https://github.com/anuraghazra/github-readme-stats)

Currently working on Self-Updating Internet Technology enabled Decentralized Apps (SUITable DApps, for short).
<!--
```mermaid
flowchart LR
  subgraph SUITable-DApps
    direction TB
        subgraph P2P-Hypercore-Protocol-HyPNS[P2P Network or Blockchain]
            direction LR
            pk  -.-> |WebRTC|Contacts[Alice: \n Gets Latest \n Merkle Root from \n swarm/pubsub Topic]
            subgraph ContactBook
                direction LR
                Contacts
            end
        end
        subgraph IPLD
            direction TB
            m1[Merkle Root] -.->|next|M[Merkle Root]
            M -.->|prev|m1
            AliceRenders
            AccessList
        end
    subgraph DApp
        direction BT
        Rendered
        AliceDApp
    end
    subgraph Wallet
        direction TB
        Encrypt <-.-> |PKI|Decrypt
        K[Re-encryption Key] --> AccessList[Access List]-->M
        AliceDecrypt[Alice uses \n re-encryption \n key to Decrypt \n shared data]
    end
  end
    M -.->  pk(Topic: Public Key \n Data: Latest Merkle Root)
  m1[Merkle Root CID] -->|User Data Ciphertext| Decrypt
  Decrypt -->|User Data Plaintext| Rendered
  m1[Merkle Root CID] -->|ES Module| Rendered
  Rendered -->|Updated User Data| Encrypt
  Encrypt-->|Updated User Data| M[New Merkle Root CID]
  Encrypt-->|Re-Encrypted Key for Alice| K
  AliceRenders[Alice: \nResolves es module +\n  data from Merkle Root]
  Contacts-->AliceRenders
  AliceRenders-->AliceDecrypt
  AliceDecrypt-->AliceDApp[Alice renders DApp +\n  Data in the browser]
```                                                                                                      
-->
<!--
**DougAnderson444/DougAnderson444** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

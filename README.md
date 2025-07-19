# 🎁 ZoraGift

## 💡 What it does  
ZoraGift lets users create personalized crypto gifts by generating AI-powered art and minting them as NFTs for special occasions like birthdays, anniversaries, or milestones. Users input a message and occasion type, and the system outputs a custom artwork that’s instantly minted on-chain.

---

## ❗ The problem it solves  
Crypto transfers often lack emotional value or personal touch. ZoraGift solves this by making crypto gifting expressive and memorable through personalized AI art NFTs. It transforms simple transactions into lasting digital mementos.

---

## 🧩 Challenges I ran into  
- Integrating Livepeer.ai’s media pipeline with dynamic user inputs  
- Handling metadata storage reliably on IPFS  
- Ensuring seamless minting with Zora’s protocol while maintaining a smooth UX  
- Making the flow user-friendly without requiring deep Web3 knowledge

---

## 🛠️ Technologies I used  
- **Livepeer.ai** – for generating AI-powered text-to-image artwork  
- **Zora Protocol** – for gas-efficient NFT minting  
- **IPFS** – for decentralized metadata storage  
- **Next.js / React** – frontend interface  
- **Ethers.js** – for contract interactions  
- **Zora’s SDK** – to manage minting and token creation

---

## 🏗️ How we built it  
We built a frontend using Next.js that allows users to input gifting data. This is sent to Livepeer.ai to generate art on the fly. The image is uploaded to IPFS and paired with metadata. Using Zora’s SDK and contract on Sepolia testnet, the generated asset is minted as an NFT and linked to the user wallet.

---

## 📚 What we learned  
- How to use media AI (Livepeer) in real-time Web3 workflows  
- Importance of designing emotionally resonant crypto applications  
- Improved understanding of dynamic metadata handling and Zora's minting process  
- How storytelling and utility can be merged in blockchain experiences

---

## 🔮 What’s next for ZoraGift  
- Integrating **SwarmZero.ai** to introduce AI agents for deeper personalization  
- Support for **multi-language prompts** and **animated gift NFTs**  
- Enable gifting through **ENS usernames or email invites**  
- Launching a **ZoraGift Gallery** where users can browse and remix gift ideas  
- Moving to **mainnet with fiat-onramp gifting** support

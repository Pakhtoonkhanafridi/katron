# Katron (Jk) – ERC-20 / BEP-20 Token

Katron (Jk) is a secure, mintable, burnable, and pausable ERC-20/BEP-20 token built with OpenZeppelin Contracts.  
This contract is production-ready and implements industry best practices for token security and compliance.

    Token Details
Name: katron  
Symbol: Jk  
Decimals: 18  
Initial Supply: 1000 Jk (minted to deployer)  
Standard: ERC-20 (Ethereum) / BEP-20 (BNB Smart Chain)  

 Features
Mintable  Owner can mint new tokens  
Burnable   Holders can destroy their tokens  
Pausable Owner can pause/unpause all transfers  
Ownable   Admin functions restricted to contract owner  
Reentrancy Protected  Minting and admin functions secured against attacks  
 
 Contract Functions

 Public (for all holders)
transfer(address to, uint256 amount) – Send tokens  
approve(address spender, uint256 amount) – Approve spending  
transferFrom(address from, address to, uint256 amount) – Transfer on behalf  
burn(uint256 amount) – Burn your tokens  
burnFrom(address account, uint256 amount) – Burn tokens with allowance  

 Owner-only
mint(address to, uint256 amount) – Create new tokens  
pause() – Halt all transfers/approvals/mints/burns  
unpause() – Resume operations  

   Security
Built with OpenZeppelin v5.x libraries  
Uses Ownable, Pausable, and ReentrancyGuard

  
Complies with ERC-20 and BEP-20 standards  
All state-changing functions emit standard events  


Deployment
 on remix.ide no installation is required.

 Install dependencies
   bash
npm install @openzeppelin/contracts

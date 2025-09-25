# Detailed Documentation

## Idea
Patients often face difficulties when registering at new hospitals.  
By using blockchain, patient records can be securely shared only between authorized hospitals.

## Flow
1. Hospital A registers patient data → stored on blockchain.
2. Hospital A grants access to Hospital B.
3. Hospital B can view summary and encrypted file pointer (CID).
4. Data privacy maintained, patients avoid repetitive registration.

## Technology
- Canton Network (for DAML smart contract)
- Encrypted off-chain storage (IPFS / S3)
- DAML contract: see `contracts/Patient.daml`
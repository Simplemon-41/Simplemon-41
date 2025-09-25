# HealthChain – Technical Details

## 🏗 Architecture
HealthChain leverages **Canton Network** to provide a secure, permissioned blockchain for healthcare records.

### Components:
1. **Smart Contract (DAML)**  
   - Defines `PatientRecord` template.  
   - Ensures that only authorized hospitals can create, update, or view patient data.

2. **Access Control**  
   - Implemented via Canton’s permissioned model.  
   - Hospitals must be registered participants.  

3. **Data Flow**
   - Patient registers at Hospital A → record stored on Canton.  
   - Hospital B can access the same patient record (with permission).  
   - No duplicate registration needed.  

---

## 🔑 Key Benefits
- **Secure & Encrypted:** All records stored with cryptographic protection.  
- **Permissioned:** Only trusted hospitals can access.  
- **Faster Registration:** Patients don’t need to re-register at each hospital.  
- **Interoperable:** Can integrate with existing hospital systems via API.  

---

## 📂 File Structure

/contracts Patient.daml        
# Smart contract template /docs DETAIL.md           # Technical explanation /mockups patient_flow.png    # Mockup of patient registration flow README.md              # Project overview LICENSE                
# MIT License

---

## 🚀 Future Improvements
- Add mobile-friendly interface for patients.  
- Build API for hospital systems to connect easily.  
- Explore integration with insurance providers.
# Day 1: Azure Environment Setup


## 📚 Topics I Learned Today

- **Azure Subscription:** 
- **Resource Groups:** 
- **Storage Accounts:** 
- **Azure Data Factory:** 
- **Where ADF fits:** 

**Key Concepts:**
- Resource Groups act like folders that group related Azure services together
- Storage Accounts provide scalable cloud storage with different redundancy options
- Azure Data Factory is the orchestration tool that will move and transform data
- All resources need unique names across Azure

---

## 🔨 Practical Tasks I Completed

### Task 1: Create Resource Group
**What I did:** Created a resource group to organize all my project resources  
**Name:** `RG-Healthcare-Project`  
**Result:** ✅ Successfully created

### Task 2: Create Storage Account
**What I did:** Set up cloud storage for healthcare data files  
**Name:** `healthdata123`  
**Configuration:** Standard performance, LRS redundancy  
**Result:** ✅ Successfully created

### Task 3: Create Azure Data Factory Instance
**What I did:** Provisioned ADF instance for building data pipelines  
**Name:** `FirstDf-project`  
**Result:** ✅ Successfully created

---

## 💡 Key Takeaways

- **Most important thing I learned today:** Azure uses a hierarchy: Subscription → Resource Group → Services. Understanding this structure is fundamental.
- **How this connects to the project:** These three resources form the foundation - Storage holds data, ADF moves data, and Resource Group keeps everything organized.
- **Real-world application:** In production environments, resource groups help with cost tracking, access control, and lifecycle management.

---

## 📚 Resources I Used

- [Microsoft Learn: Azure Fundamentals](https://learn.microsoft.com/azure/fundamentals)
- Azure Portal documentation
- Azure naming conventions guide

---

## ⏭️ Tomorrow's Plan (Day 2)

**Topic:** ADF UI Deep Dive  
**Goals:**
- [ ] Navigate ADF Studio interface
- [ ] Explore Author, Monitor, Manage tabs
- [ ] Create first dummy pipelines
- [ ] Understand pipeline concepts




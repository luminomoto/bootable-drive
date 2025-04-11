# 🔧 How to Make a Bootable USB with OS Installation + Bypass Feature

>  **Before you start:** Make sure you have a **stable internet connection**.

---

###  Requirements:

1. **Flash Drive** – At least **8GB recommended**  
   _(Avoid cheap fake ones from Shopee for ₱300 — ingat kanalang)_

2. **ISO File** – Your OS installer in `.iso` format

---

### 🛠️ Step-by-Step Guide:

#### **Step 1:**  
[Download Rufus 4.7](https://github.com/pbatard/rufus/releases/download/v4.7/rufus-4.7.exe)

#### **Step 2:**  
Insert your flash drive into your PC or laptop.

#### **Step 3:**  
Open `rufus.exe`

#### **Step 4:**  
Click **"SELECT"** and load your **ISO file**

---

### 🔧 Rufus Settings

#### **Partition Scheme & Target System**  
- **MBR** → for **Legacy BIOS**  
- **GPT** → for **UEFI systems**  
_**(Rufus auto-detects this, but you can change it manually if needed)**_

#### **File System & Cluster Size**  
- File System: **FAT32** or **NTFS** (Rufus chooses best option)  
- Cluster Size: Leave at **Default**

---

#### **Step 5:**  
Click **Start** to begin the bootable creation process.

>  *Optional: You can choose what bypass options you'd like (e.g., TPM, Secure Boot, RAM, etc.)*

---

###  After it's Done:
- Wait for the process to complete.
- Safely **eject your flash drive**.
- You're good to go!

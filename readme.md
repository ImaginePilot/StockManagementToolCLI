### 1️⃣ **Create empty folder & copy all 93 files**  
→ Copy `vm/vm_separated.7z.001` → `vm_separated.7z.333` into a **new empty folder** (e.g. `C:\StockVM`)

### 2️⃣ **Extract with 7-Zip**  
- **Windows**: Right-click `001` file → `7-Zip > Extract Here`  
- **macOS/Linux**: Terminal in folder → run  
  ```bash
  7z x vm_separated.7z.001
  ```

### 3️⃣ **Run the VM**  
1. Open **VMware Workstation Player** (install if needed)  
2. Click `Open a VM` → Select `.vmx` file in extracted folder  
3. Power on → Use credentials:  
   - **User**: `c43`
   - **Pass**: `123456`  
4. Start postgres (password: postgres):
  ```sudo su postgres
     bash
     postgres
     /c mydb
 ```
5. Start program `/data/main`

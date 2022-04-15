# custom-steam-status

### ***Easy to use "custom status" for Steam***

---
### **Purpose**:

Takes a custom `.bat` file/script which uses the `IEXPRESS` script to compile an exe, which can be added as a non-Steam game to display a "custom status message" so to speak.

### **Requirements**:

Requires zero dependencies or knowledge
Windows or an environment capable of running `.bat` and `.exe` files.

Makes use of npocmaka's IEXPRESS script: 
https://github.com/npocmaka/batch.scripts/edit/master/hybrids/iexpress/bat2exeIEXP.bat

### **Cloning + Building from Source**:
HTTPS: `git clone https://github.com/Defirence/custom-steam-status.git`

SSH: `git clone git@github.com:Defirence/custom-steam-status.git`

### **Usage**:

`bat2exeIEXP.bat batch_script_name.bat desired_exe_name.exe`

The compiled .exe will be stored in the current working directory, the status message displayed on Steam is determined by the name of the .exe file.

### **Licences**:
custom-steam-status: No Licence

npocmaka's IEXPRESS: MIT Licence
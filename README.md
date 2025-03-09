# 📌 PowerShell Tips for Hackers  

🚀 **This repository powers the tips section of [PowerShellForHackers.com](https://powershellforhackers.com/tips)!**  

This is a community-driven collection of **useful PowerShell tips** for hacking, automation, and scripting. Each tip you submit **automatically updates the website** and helps others learn cool PowerShell tricks!  

---

## **📜 How It Works**  
Each **tip** in this repo is stored as an **individual file** inside the `/tips/` folder.  
These files are **used to populate the tips page**:  
👉 [https://powershellforhackers.com/tips](https://powershellforhackers.com/tips)  

💡 **The filename becomes the tip’s unique name!**  

For example, if you create a file named:  
```
high-cpu-processes
```
It will be displayed on the site as:  
```
https://powershellforhackers.com/tips/#high-cpu-processes
```

---

## **📝 Submission Format**  
Each tip file **must** follow this simple format:  

```
#code:
Get-Process | Where-Object {$_.CPU -gt 1000}

#description:
This tip shows how to find processes consuming more than 1000 CPU units.
```

🔹 **Everything directly below `#code:` is the PowerShell code.**  
🔹 **Everything directly below `#description:` is the explanation.**  
🔹 **No need to add file extensions!**  

### **✅ Example Tip**  
File: `/tips/list-running-services`  
```
#code:
Get-Service | Where-Object { $_.Status -eq 'Running' }

#description:
List all currently running services on the system.
```

---

## **📥 How to Submit a Tip**  
1. **Fork this repository**  
2. **Create a new file inside `/tips/`** (name it after the tip)  
3. **Write your PowerShell tip using the correct format**  
4. **Commit and submit a Pull Request**  

Your tip will be reviewed and added to [PowerShellForHackers.com](https://powershellforhackers.com/tips) once approved! ✅  

---

## **🔧 How This Works Behind the Scenes**  
💡 A **PowerShell script automatically**:  
✅ Pulls new tips from GitHub  
✅ Converts them into **Base64** for safe storage  
✅ Generates `tips-data.js` for the website  
✅ Updates the live tips page  

This means **no complex formatting issues**, and you can **submit tips easily without worrying about escaping characters**. 🎯  

---

## **🛠 Contributing Rules**  
✅ Keep tips **short, useful, and relevant**  
✅ **No duplicate tips** (search first!)  
✅ Use **clean and readable PowerShell code**  
✅ Keep the **description clear and concise**  

---

## **👨‍💻 Maintained By**  
This project is part of **[PowerShellForHackers.com](https://powershellforhackers.com)**, created by **[i am jakoby](https://twitter.com/i_am_jakoby)**.  

Enjoy hacking with PowerShell! 🖥️💀🔥  

---

## **🔗 Connect & Support**  
🐦 Twitter: [@iamjakoby](https://twitter.com/iamjakoby)  
🖥️ Website: [PowerShellForHackers.com](https://powershellforhackers.com)  

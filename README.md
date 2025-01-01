# Common Windows Forensic Artifacts

<h2>Description</h2>
In this Digital Forensics task, I downloaded kape and used the gkape graphical kape tool to extract registry artifacts from my windows 10 vm to load the clean hives into registry explorer. 

<h2>Languages and Utilities Used</h2>

- <b>gkape</b>
- <b>Registry Explorer</b>

<h2>Environments Used </h2>

- <b>Windows 10 Enterprise</b> 

<br />
<br />
Using gkape to target the C:\ drive for ym widows 10 vm, destination to a Cases folder, using the find function to look for registry and selecting all relevant registry hives, then executing. 

![1) gkape suspect registry extraction](https://github.com/user-attachments/assets/742a9488-4327-428c-ad24-6308222a82ce)

<br />
<br />
Showcasing the Windows System32 config logs extracted. 

![2) windows system 32 registry logs saved](https://github.com/user-attachments/assets/d95be008-0c10-49bf-ab0c-aa77bb780f19)

<br />
<br />  
Showcasing the NTUSER.DAT logs extracted. 

![3) ntuser dat files](https://github.com/user-attachments/assets/b9ab292d-7241-42f7-bd76-e661a426c4dc)

<br />
<br />
Showcasing the UsrClass logs extracted. 

![4) user class dat files](https://github.com/user-attachments/assets/02fa3a4b-9199-4fb1-9531-1702b864e558)

<br />
<br />
In Registry Explorer, I uploaded both ntuser.dat logs into a combined cleaned hive and saved the clean hive onto a clean hive folder. 

![5) registry explorer loading clean hive data](https://github.com/user-attachments/assets/5071e83f-da8b-4729-9a8e-6bdd6b474ca0)

<br />
<br />  

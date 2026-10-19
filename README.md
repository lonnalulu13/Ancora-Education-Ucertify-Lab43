# Ancora-Education-Ucertify-Lab43
# Stopping Permissions Inheritance

> **Original Lab Source**
> 
> This lab was available through:
>
> [https://ancoraeducation.ucertify.com/app/?func=navigate_items&item_sequence=4]

## Objective of the Lab
In this lab, you will learn to stop permissions inheritance. Permissions inheritance can be defined as the permission settings of an object in a site collection passed on to the children of that object. 
## Instructions 
### STEP 1 
From the bottom-left bar, click the WIN16 tab, and then click On/Connect to power on the machine. 
### STEP 2 
From the desktop, open This PC. 
### STEP 3 
In the This PC window, double-click Local Disk (C:). 
### STEP 4 
Right-click Project and then click Properties.
### STEP 5
In the Project Properties dialog box, click the Security tab and then click Advanced. 
### STEP 6 
In the Advanced Security Settings for Project dialog box, you can observe that the folders are inherited from C:\.
### NOTE
* Here C:\ represents Inherited permission. Inherited permissions are those that are propagated to an object from a parent object.
### STEP 7 
In the Advanced Security Settings for Project dialog box, click Disable inheritance.
### STEP 8 
At the Block Inheritance prompt, click Convert inherited permissions into explicit permissions on this object. 
### STEP 9 
You will observe that after disabling inheritance, the permissions entries inherited from changed to None. 
### Note 
* Here None represents Explicit permission. Explicit permissions are those that are set by default on non-child objects when the object is created, or by user action on non-child, parent, or child objects.
### STEP 10 
Click Apply, and then click OK. 
### STEP 11 
In the Project Properties dialog box, click OK. 
### STEP 12 
Close all windows.
## Disclaimer

This repository is for **educational and personal learning purposes only**.  

The original lab content belongs to **uCertify / Ancora Education** and remains their copyrighted material.  
This repository is not affiliated with, endorsed by, or sponsored by uCertify or Ancora Education.  

No copyright infringement is intended.  
Use of any tools or techniques mentioned here should only be performed in authorized, legal environments.

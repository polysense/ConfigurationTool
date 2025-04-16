# ConfigurationTool

This is a configuration tool provided by Polysense, which can configure parameters for devices produced by Polysense, such as communication type, reporting cycle, and can also upgrade drivers, firmware, etc

You can use configuration tools to debug devices, view configurations, restore factory configurations, etc

ConfigurationTool.exe is the latest runnable configuration tool, You can also download historical versions from the history folder.

## Screenshot
![Config00](/image/Config_00.png) 
![Config01](/image/Config_01.png)
![Config02](/image/Config_02.png)
![Config03](/image/Config_03.png)
![Config04](/image/Config_04.png)

# Environment dependent
* The Configuration Tool runs and depends on the environment .NET Framework >= 4.0

* Download and install from the public drive at the download address http://ota.polysense.online/wincc/depend/dotNet4.rar

Note: If you are using Windows 7, please do not use. NET Framework 4.5 as it is not possible to upgrade drivers when using the configuration tool. Please use. NET Framework 4.0 or. NET Framework 4.8 instead

# Solution to misreport in Windows Defender antivirus software
When downloading the Configuration Tool from the official website, some machines may be <font color="red">falsely reported</font> as viruses by the antivirus software Windows Defender, causing interference and deletion of the program. <font color="red">It is hereby declared</font> that the configuration tool is only used to configure device parameters and will <font color="red">not</font> engage in illegal task destruction behavior on client computers. Although we understand the behavior of antivirus software, it is also helpless. We will submit an appeal as soon as possible after the antivirus software reports a false alarm (domestic antivirus software usually takes 3 working days to resolve, while foreign antivirus software takes about 15 working days).

* Step 1: Find a shield icon in the bottom right corner of Windows and click on it.
* Step 2: Turn off real-time protection and cloud provided protection. Click "Add or Remove Exclusions" to set the desktop folder (or other folder) as an exclusion item
* Step 3: Download the configuration tool from the official website and copy it to the folder where the exclusion item was added in the previous step.
* Step 4: reopen the real-time protection and cloud provided protection in step 1.
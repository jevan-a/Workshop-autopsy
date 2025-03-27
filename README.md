
# Workshop on Digital Forensics
Installation and Usage of Sleuth Kit & Autopsy
```
Register Number: 212222040020
Name: Ashwinkumar S
```
## Introduction
Digital forensics involves extracting and analyzing data from digital devices to investigate cybercrimes. Sleuth Kit and Autopsy are widely used open-source tools for forensic analysis.

## Installation Steps
### A. Installing Sleuth Kit & Autopsy on Windows
1.Download Autopsy
- Visit Autopsy Official Website and download the latest version.
- Double-click the downloaded file and follow the on-screen instructions.
![{660CA88E-DE17-4556-89B5-38945EF3AA31}](https://github.com/user-attachments/assets/d5cf2c90-4fc9-453e-93ff-ef64378dd232)

2.Installation Process
- Launch Autopsy to check if it works correctly.
![Screenshot (163)](https://github.com/user-attachments/assets/ecd94a00-aec6-49cd-ae99-374181d47f39)

  
- Choose Directory
- ![Screenshot (164)](https://github.com/user-attachments/assets/c7686c1e-08e1-451c-8968-c34ddde5d8b2)

  
- Give install
 ![Screenshot (165)](https://github.com/user-attachments/assets/adaa80eb-e547-48f9-8b0b-4615580d4b6d)
![Screenshot (166)](https://github.com/user-attachments/assets/02f5e31d-04e7-4128-852d-a8b07ebb458e)


- Successfully installed
- ![Screenshot (168)](https://github.com/user-attachments/assets/9f872b0c-c0a2-4e8b-8a37-a6c05e2900ca)


- Autopsy Interface
- ![Screenshot (169)](https://github.com/user-attachments/assets/9c549a9a-531b-42e7-83b9-d6a276c280d3)



## B. Installing Sleuth Kit Separately (Optional)
Download Sleuth Kit from www.sleuthkit.org/sleuthkit/download.php.
![{FAC04ED6-02D9-4D2A-A73C-CDADA79B7939}](https://github.com/user-attachments/assets/216ff656-18eb-497f-a795-3ca4112e758c)

Extract and install it manually if needed.
Add the installation directory to the system PATH for easy command-line access.
![Screenshot (170)](https://github.com/user-attachments/assets/9a7d49e6-0da9-4226-adc8-162b580eb3a3)



## Using Autopsy to Analyze a Disk or Folder
## 1.Launch Autopsy and Set Up a New Case:

- Run Autopsy as Administrator.

- Click Create New Case.
![Screenshot 2025-03-19 222716](https://github.com/user-attachments/assets/4028e969-add1-46c4-beb2-3f336c7dcd3d)

- Enter a case name (e.g., Autopsy1).
- Select a location for the case folder → Click Next → Finish.
  ![Screenshot (154)](https://github.com/user-attachments/assets/4a96ebdf-105c-45b2-84a4-ff771da86b50)

- Add optional information
  ![Screenshot (152)](https://github.com/user-attachments/assets/6a193fd6-5314-4eba-aeaf-e0d1ab37ef74)



## 2.Add the Partition as Evidence:

- Click Add Data Source → Choose Host.
   ![Screenshot 2025-03-19 223322](https://github.com/user-attachments/assets/3ad0612b-655b-406c-ab63-95912238b112)


- Select Local Disk → Click Next.
   ![Screenshot 2025-03-19 223337](https://github.com/user-attachments/assets/8ed1cda5-f34d-491b-8255-c59c62eadaa0)


- Choose Disk → Select the VHD drive (Drive1).
  ![Screenshot (157)](https://github.com/user-attachments/assets/92a6df6e-0dfa-45c4-8b4f-7b8494534c23)


- Click Next → Keep the default settings → Click Finish.
  ![Screenshot 2025-03-19 224106](https://github.com/user-attachments/assets/3feb68c2-3a3a-4e21-b3b8-11f4dfac0990)


- Allow Autopsy to process the disk.
## C. Running the Analysis
1.Start processing the disk or folder.

2.Wait for Autopsy to generate reports.

3.Analyze deleted files, metadata, and hidden data in the results.

## Using Sleuth Kit from Command Line
### A. Ckecking sleuthkit Version
```
sh
fls -V
```
![Screenshot (170)](https://github.com/user-attachments/assets/163a27e9-5f20-4373-bb1c-6cdb74929179)


### B. Lists partition layout
```
sh
mmls
```
![Screenshot (171)](https://github.com/user-attachments/assets/6a3fe9a0-bd37-4621-8caf-2e9e57c7f742)


### C. Lists files and directories
```
sh
fls
```
![Screenshot (171)](https://github.com/user-attachments/assets/801210af-ba38-43b3-939d-e8eed721912f)


## Conclusion
By following these steps, you can install Sleuth Kit & Autopsy and analyze a disk or folder from the C drive. These tools help in digital investigations, allowing forensic experts to recover and analyze digital evidence.


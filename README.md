# Install Autopsy and Analyze the Disk File and Folder Configuration

## AIM
To install **Autopsy** and use it to analyze the disk’s file and folder configuration for forensic investigation.

## REQUIREMENTS
- **Operating System**: Windows 10/11, macOS, or Linux
- **Tools**:  
  - [Autopsy Digital Forensics Platform](https://www.autopsy.com/)  
  - Optional: Sleuth Kit CLI tools for deeper analysis
- **Test Data**: Disk image file (`.dd`, `.img`, `.E01`)

## ARCHITECTURE DIAGRAM
```mermaid
flowchart TD
    A[Disk Image / Physical Drive] --> B[Install Autopsy]
    B --> C[Create New Case in Autopsy]
    C --> D[Add Data Source: Disk Image]
    D --> E["Autopsy Modules Run: File System, Metadata, Keywords"]
    E --> F[File & Folder Structure View]
    F --> G[Export / Recover Files]
```
## DESIGN STEPS:
### Step 1:
Download Autopsy from the official website and install it on your system.

### Step 2:
Launch Autopsy and create a new case.

### Step 3:
Add your disk image or physical drive as the data source.

### Step 4:
Allow Autopsy to run its built-in ingest modules (file system analysis, hash lookup, keyword search, metadata extraction).

### Step 5:
View the file and folder hierarchy in the left-hand tree panel.

### Step 6:
Export or recover files if required for the investigation.

## PROCEDURES

1. Download Autopsy from autopsy.com.
2. Install and launch the application.
3. Select **New Case → Name your case → Choose case folder**.
4. Click Add **Data Source → Select Disk Image → Browse to file**.
5. Choose ingest modules (file system, metadata, hash lookup, keyword search).
6. Wait for processing to finish.
7. Explore file/folder structure in the navigation pane.
8.Export selected files for further examination.

## OUTPUT:
File and Folder Configuration Analysis Results
<img width="1018" height="658" alt="Screenshot 2026-08-19 202311" src="https://github.com/user-attachments/assets/6194cdbf-32b5-4535-9466-4b2b29038373" />

<img width="1920" height="1020" alt="2026-08-21" src="https://github.com/user-attachments/assets/e0c3f29c-0534-44cf-980d-e5dc12883f47" />

<img width="635" height="319" alt="Screenshot 2026-08-21 202103" src="https://github.com/user-attachments/assets/bbc10370-f8c3-4df6-a4ae-63fbf7cf45f8" />

<img width="1467" height="1014" alt="Screenshot 2026-08-21 222738" src="https://github.com/user-attachments/assets/b36eef48-c3ad-4e4c-8415-6de7dd67a668" />

<img width="1463" height="1011" alt="image" src="https://github.com/user-attachments/assets/eb22f34f-a0db-403a-9af0-e1494f0a66b9" />

<img width="1663" height="918" alt="Screenshot 2026-08-21 223919" src="https://github.com/user-attachments/assets/294761de-6200-48fa-84ac-14ac6bd3ba56" />



## RESULT:
Autopsy was installed successfully and used to analyze disk, file, and folder configuration for forensic investigation.

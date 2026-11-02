# Install Autopsy and Analyze the Disk File and Folder Configuration
## NAME: SWARNA PRIYA S
## REG.NO: 212225040447
## DATE: 02.11.2026
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

## PROGRAM(Windows)

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

<img width="1920" height="1200" alt="Screenshot 2026-11-02 104121" src="https://github.com/user-attachments/assets/947fdbd0-e550-45f1-a8aa-af12a143cd20" />


<img width="1920" height="1200" alt="Screenshot 2026-11-02 104700" src="https://github.com/user-attachments/assets/b7a435a9-5a68-4bd5-94c0-8fa942ec79c1" />


<img width="1920" height="1200" alt="Screenshot 2026-11-02 104735" src="https://github.com/user-attachments/assets/044e42ef-438c-43ea-8303-642d12e5ad24" />



<img width="1920" height="1200" alt="Screenshot 2026-11-02 104816" src="https://github.com/user-attachments/assets/3ecf41fe-20b2-43db-98ba-2ce070239115" />

<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/f7259443-0cb4-489b-843c-0ae8a97e3d23" />


## RESULT:
Autopsy was installed successfully and used to analyze disk, file, and folder configuration for forensic investigation.

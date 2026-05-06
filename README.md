# EC OTDR Viewer
A small Android app for viewing and analyzing OTDR .sor files. It supports parsing the SOR file format, visualizing the fiber trace and event information, and generating PDF reports.
The app is still under development, with ongoing improvements to parsing, visualization, and report generation.

This application performs all data processing locally on the device. It does not require an internet connection and does not collect, store, or transmit any user data.
Welcome your feedback, feature requests, and bug reports. Please email me anytime.
Email: embeddedchan@gmail.com

Developed and maintained by **EmbeddedChan**.

## 📥 Download

Latest Version:

[Download EC-OTDR-Viewer-v0.9.1.apk](https://github.com/EmbeddedChan/otdr-sor-parser/raw/main/apk/EC-OTDR-Viewer-v0.9.1.apk)

# 📡 EC OTDR Viewer – Feature Overview

EC OTDR Viewer is a lightweight and powerful fiber optic analysis tool designed for OTDR trace visualization, link analysis, and telecom engineering utilities. It provides an all-in-one toolkit for fiber engineers, installers, and network testers.

---

## 📊 SOR Parser & OTDR Trace Viewer

### 📁 SOR File Management
- Import and manage Telcordia SR-4731 standard SOR files  
- Multi-file handling for fiber link comparison (Coming soon) 

### 📈 OTDR Trace Visualization
- High-performance trace curve rendering  
- Zoom, pan, and event inspection support  
- Multi-trace comparison (up to multiple fibers)(Coming soon)  

### 📄 PDF Report Export
- Generate professional OTDR test reports  
- Include trace graphs and event summaries  
- Easy sharing and documentation workflow  

---

## 🔗 Link Budget Module

### ⚡ Basic Receiver Power Check
- Quickly verify optical receiver power levels  
- Simple pass/fail analysis for field use  

### 🌐 High-Speed Optical Link Analysis
- Full link budget calculation  
- Supports multi-span fiber networks  
- Designed for telecom and data center planning  

---

## 🎨 Fiber Optic Color Code Module

### 🔍 Color Code Lookup
- Support for common fiber standards (e.g. TIA-598)  
- Fast reference for fiber identification  

### 🧩 Fiber Mapping Tool
- Map fibers inside loose tube / ribbon structures  
- Visualize fiber organization and numbering  
- Supports multi-fiber cable structures  

---

## 🛠 Tools Module

### 🔌 Optical Power Converter
- dBm ↔ mW conversion  
- Fast and accurate power unit translation  

### ➗ Splitter Loss Calculator
- Calculate insertion loss for optical splitters  
- Support common split ratios (1:2, 1:4, 1:8, etc.)  

### 📡 WDM Tool (ITU Grid Supported)
- Wavelength ↔ Frequency conversion  
- ITU channel mapping (DWDM/CWDM grid support)  

### ⏱ OTDR Time–Distance Converter
- Convert pulse time to fiber distance  
- Useful for OTDR event interpretation  

---

## 🚀 Designed For

- Fiber optic engineers  
- Telecom field technicians  
- Network installation teams  
- Optical lab testing  
- Data center infrastructure engineers

## 🖼 UI Preview

![Screen 1](images/Screenshot_22.jpg)

![Screen 1](images/Screenshot_21.jpg)

![Screen 1](images/Screenshot_12.jpg)

![Screen 1](images/Screenshot_19.jpg)

![Screen 1](images/Screenshot_17.jpg)

![Screen 1](images/Screenshot_18.jpg)

![Screen 1](images/Screenshot_23.jpg)

## Version History
### v0.9.1 
- Added fiber optic color code lookup and mapping module
 
### v0.8.2 
- Added Link Budget: save the current link configuration 
- Added link topology diagram in the OTDR Trace view
- Added Splitter Loss Calculator
- Added WDM Wavelength ↔ Frequency + ITU Channel converter (incl. ITU grid mapping)

### v0.8.1  - Tools module added
- Added optical power converter 
- Added ODTR time distance converter

### v0.7.2
 Fixed: event data issues in OTDR SOR PDF report

### v0.7.1  - Link Budget module added
- Added optical link budget calculation engine
- Basic receiver power check
- High-speed optical link analysis


### v0.6.5 
- Added filtering for file list
- Added conditional validation for SOR file import
### v0.6.3

#### PDF Report
- Fixed: Fiber type
- Added: Span length, average loss
- Updated: "Total Loss" → "Span Loss"

### v0.6.2

#### Added
- SOR File Management
- MSOR File Import

#### Improved
- PDF report:
  - The following fields can now be edited:
    1. Report Title
    2. Cable ID
    3. Fiber ID
    4. Location A
    5. Location B
    6. Cable Code
    7. Operator

### v0.3.0
Added
- PDF report export (Pro: no watermark)
- File name display

### v0.2.1
- Initial release


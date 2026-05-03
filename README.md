# EC OTDR Viewer
A small Android app for viewing and analyzing OTDR .sor files. It supports parsing the SOR file format, visualizing the fiber trace and event information, and generating PDF reports.
The app is still under development, with ongoing improvements to parsing, visualization, and report generation.

This application performs all data processing locally on the device. It does not require an internet connection and does not collect, store, or transmit any user data.

Developed and maintained by **EmbeddedChan**.

## 📥 Download

Latest Version:

[Download EC-OTDR-Viewer-v0.8.2.apk](https://github.com/EmbeddedChan/otdr-sor-parser/raw/main/apk/EC-OTDR-Viewer-v0.8.2.apk)

## Version History

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


## 🖼 UI Preview

![Screen 1](images/Screenshot_22.jpg)

![Screen 1](images/Screenshot_21.jpg)

![Screen 1](images/Screenshot_12.jpg)

![Screen 1](images/Screenshot_19.jpg)

![Screen 1](images/Screenshot_17.jpg)

![Screen 1](images/Screenshot_18.jpg)

![Screen 1](images/Screenshot_23.jpg)

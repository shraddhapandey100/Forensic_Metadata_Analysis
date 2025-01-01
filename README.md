# WhatsApp Metadata Analysis Framework for Forensics

This project provides a comprehensive framework for analyzing the metadata of recovered deleted WhatsApp files on Windows. The framework assists forensic investigators in reconstructing events and preparing legal reports based on metadata extracted from WhatsApp files.

## Features:
- **Data Acquisition**: Extract data using forensic tools like FTK Imager and Autopsy.  
- **Metadata Extraction**: Retrieve crucial metadata using ExifTool and other methods.  
- **Metadata Analysis**: Analyze data using machine learning techniques for event reconstruction.  
- **Data Visualization**: Present findings effectively with Python-based visualizations.  
- **File Carving**: Recover deleted files from unallocated disk space.

## Prerequisites:
- Python 3.8+
- FTK Imager, Autopsy, and ExifTool installed on your machine.
- Install required Python libraries:
  ```bash
  pip install -r requirements.txt

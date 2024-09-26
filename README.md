# Bulk IP Translator

<div align="center">

![Python](https://img.shields.io/badge/3.6+-Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Tkinter](https://img.shields.io/badge/Tkinter-3776AB?style=for-the-badge&logo=python&logoColor=white)

A powerful tool for analyzing bulk IP addresses into detailed information.

</div>

## Features

🌐 Check multiple IP addresses in bulk.  
📊 Support for Excel (.xlsx) and CSV input files   
🚀 Multithreaded processing for enhanced speed   
📁 Drag and drop interface for easy file input   
📈 Live progress tracker  
🔄 Customizable output format (CSV or JSON)   
⚙️ Adjustable number of worker threads   

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/clashhsalc/Bulk-IP-translator.git
   cd Bulk-IP-translator
   ```

2. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Run the application:
   ```bash
   cd dependencies 
   py main.py
   ```

2. The GUI will open. You can:
   - Drag and drop an Excel (.xlsx) or CSV file containing IP addresses
   - Select the desired output format (CSV or JSON)
   - Set the number of max workers for multithreading
   - Click "Save" to apply the max workers setting (50 is recommended)

3. Once you drop a file, the application will start processing the IP addresses
4. Monitor the progress bar
5. When complete, find the output file in the same directory as the input file

## Input File Format

Your input file should be either an Excel (.xlsx) or CSV file with IP addresses in the first column. No header is required.

Example:
```
192.168.1.1
10.0.0.1
8.8.8.8
8.8.4.4
1.1.1.1
220.223.24.21
```

## Output

The application will generate an output file with the following information for each IP:

- IP address
- Country
- Country code
- City
- ISP
- Latitude
- Longitude
- ...and more

## Requirements

- Python 3.6+
- pandas
- requests
- tkinter
- tkinterdnd2
- Pillow

## API Usage

This application uses the [IPLocation.net API](https://api.iplocation.net/). Please be aware of their usage terms and limitations.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

---

<div align="center">
a GPCSSI project made with ❤️ 
</div>

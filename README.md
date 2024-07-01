# ForensicInstaller

ForensicInstaller is a Bash script that automates the installation of digital forensics and related tools on Kali Linux. It ensures your system is up-to-date and equipped with essential tools for forensic analysis.

## Features

- **System Update and Upgrade**: Ensures the system is updated before installing tools.
- **Tool Installation**: Installs popular digital forensics tools including Autopsy, Wireshark, Sleuth Kit, and more.
- **Logging**: Logs installation activities to `install_tools.log` for reference.

  ## Tools Included

- **Autopsy**: A graphical interface to The Sleuth Kit for analyzing disk images.
- **Wireshark**: A network protocol analyzer for network troubleshooting, analysis, and software development.
- **ExifTool**: A tool for reading, writing, and editing meta information in files.
- **Sleuth Kit**: Tools for forensic analysis of volumes and filesystems.
- **Volatility**: A memory forensics framework for analyzing RAM dumps.
- **hashdeep**: A tool for recursive hashing of files.
- **osquery**: SQL-powered operating system instrumentation, monitoring, and analytics.
- **Guymager**: A forensic imager for media acquisition.
- **RegRipper**: A tool for extracting information from Windows registry hives.
- **avml**: A tool for acquiring volatile memory from Linux systems.
- **GRR Rapid Response (grr)**: Remote live forensics and incident response.
- **memdump**: A memory dumper for Linux.


## Usage

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/Securegarv/ForensicInstaller.git
   cd ForensicInstaller
2. **Make the Script Executable:**
   ```bash
   chmod +x forensic-tool.sh
3. ***Run the Script with Superuser Privileges:***
   ```bash
   sudo ./forensic-tool.sh
   

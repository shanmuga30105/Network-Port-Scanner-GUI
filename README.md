# Network-Port-Scanner-GUI
A **Network Port Scanner GUI** is a graphical application that allows users to scan a target device or network to identify open, closed, or filtered ports in an easy, visual way. Unlike command-line tools, it provides buttons, input fields, and real-time results, making it user-friendly for beginners. 
A lightweight TCP port scanner with a graphical user interface built with Python and Tkinter.
Features :
* Simple 3-field interface – enter a target host, start port, and end port
* Multi-threaded scanning – up to 500 concurrent threads for fast results
* Service identification – automatically labels well-known ports (FTP, SSH, HTTP, HTTPS, MySQL, RDP, etc.)
* Real-time progress – progress bar and elapsed-time counter update live during a scan
* Stop at any time – cancel a running scan gracefully
* Save results – export discovered open ports to a .txt file
* Cross-platform – runs on Windows, macOS, and Linux
  Requirements :
  * Python 3.7 or newer
  *Tkinter (included in the standard Python distribution; on Debian/Ubuntu install python3-tk)
   No third-party packages are required.
Installation :
* git clone https://github.com/techtrainer20/nmap_portscan_gui.git
cd nmap_portscan_gui
Usage :
 python portscanergui.py
* Enter the Target – an IP address (e.g. 192.168.1.1) or hostname (e.g. scanme.nmap.org).
* Set the Start Port and End Port (defaults: 1 – 1024).
* Click Start Scan. Open ports appear in real time in the results pane.
* Click Stop to cancel a scan early.
* After a scan completes, click Save Results to write the open-port list to a text file.
  






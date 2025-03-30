# WiFi-Network-Scanner
Created By     : x_4rch4n63l_x
Created On     : 3/30/2025 - 3:40AM
Script Purpose : To scan and display available WiFi networks using the 'netsh wlan' 
                 command on Windows systems.
Description    : This script fetches and displays real-time details of available WiFi
                 networks by executing the 'netsh wlan show networks mode=bssid' 
                 command. It provides raw network information in the console output.
Features       : - Scans available WiFi networks and lists details.
                 - Basic error handling to manage issues during command execution.
                 - Lightweight script designed for quick scanning purposes.
Requirements   : - Operating System: Windows
                 - Python 3.x
                 - Required Libraries: 'subprocess' (default Python library)
                 - Command-line access and permissions to execute 'netsh' commands.

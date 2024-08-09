# Zeek Installation and Usage Guide

1. **Install Zeek.**

2. **Run Zeek to monitor traffic on the chosen interface.**

3. **Zeek will create log files in the current directory. List the files to see the generated logs.**

4. **Inspect the `conn.log` file. Use any text editor. Identify some key fields like `ts`, `id.orig_h`, `id.resp_h`, `proto`, `duration`, `orig_bytes`, `resp_bytes`.**

5. **Explore Sample Scripts. Zeek comes with several sample scripts located generally in the `/usr/share/zeek/scripts` directory. Explore these scripts to get a feel for the syntax and functionalities.**

6. **Create a Zeek script. Create a new file named `test-conn.zeek`. Write the script to print a message when a connection is established.**

7. **Execute the script with Zeek on a PCAP file or live traffic. If you don't have a PCAP file, you can download a sample one from Wireshark Sample Captures or use a Wireshark PCAP from your own capture.**



![1](https://github.com/user-attachments/assets/52bf6db1-79f4-4d3e-92da-a8bf4165aaaa)

![2](https://github.com/user-attachments/assets/f3c87e7c-4e93-4978-a244-fb73a01c0b78)
![3](https://github.com/user-attachments/assets/073e2640-2ece-4684-8491-40a44a95d834)
![4](https://github.com/user-attachments/assets/72b58fb3-160c-49ce-bb91-a1769df64e47)
![5](https://github.com/user-attachments/assets/695ab6ba-9fea-4956-8cbe-53f9c7b1c008)
![6](https://github.com/user-attachments/assets/87a4adf8-e094-4705-98ef-03bfc9d5b230)
![7](https://github.com/user-attachments/assets/a957a4dd-ab8e-49e1-8c18-31ae13ad9306)
![8](https://github.com/user-attachments/assets/27e55932-a559-4a7f-9e3b-ad571b0f4be8)
![9](https://github.com/user-attachments/assets/da157eec-72d5-4f56-9cdd-81d392435bfb)

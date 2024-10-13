# Dumping-and-Cracking-SAM-Hashes-to-Extract-Plaintext-Passwords

## Tools:
1. PwDump7, tool untuk mengekstrak password hashes.
2. Ophcrack, tool untuk crack password dan menerima text password.
3. vista free, berisi data password crack untuk melakukan bruteforce.

## Langkah-langkah
1. Jalankan **Command Prompt** sebagai administrator.
![Screenshot 2024-10-13 195544.png](https://github.com/SyahrulWijaya/Dumping-and-Cracking-SAM-Hashes-to-Extract-Plaintext-Passwords/blob/main/Screenshot%202024-10-13%20195544.png?raw=true).
2. Lalu ketik `wmic useraccount get name,sid` dan tekan enter.
![Screenshot 2024-10-13 195707.png](https://github.com/SyahrulWijaya/Dumping-and-Cracking-SAM-Hashes-to-Extract-Plaintext-Passwords/blob/main/Screenshot%202024-10-13%20195707.png?raw=true)
3. Jalankan program **PwDump7.exe** yang sudah anda download sebelumnya
![Screenshot 2024-10-13 201000.png](https://github.com/SyahrulWijaya/Dumping-and-Cracking-SAM-Hashes-to-Extract-Plaintext-Passwords/blob/main/Screenshot%202024-10-13%20201000.png?raw=true)
4. Ketikkan perintah `PwDump7.exe > C:\hashes.txt` untuk mengcopy output dari perintah `PwDump7.exe` ke dalam file txt bernama hashes.txt.
![Screenshot 2024-10-13 201129.png](https://github.com/SyahrulWijaya/Dumping-and-Cracking-SAM-Hashes-to-Extract-Plaintext-Passwords/blob/main/Screenshot%202024-10-13%20201129.png?raw=true)
![Screenshot 2024-10-13 201155.png](https://github.com/SyahrulWijaya/Dumping-and-Cracking-SAM-Hashes-to-Extract-Plaintext-Passwords/blob/main/Screenshot%202024-10-13%20201155.png?raw=true)
5. Buka aplikasi OphCrack dan load PWDUMP file, dan masukkan file hashes.txt sebelumnya
![Screenshot 2024-10-13 201732.png](https://github.com/SyahrulWijaya/Dumping-and-Cracking-SAM-Hashes-to-Extract-Plaintext-Passwords/blob/main/Screenshot%202024-10-13%20201732.png?raw=true)
![Screenshot 2024-10-13 201805.png](https://github.com/SyahrulWijaya/Dumping-and-Cracking-SAM-Hashes-to-Extract-Plaintext-Passwords/blob/main/Screenshot%202024-10-13%20201805.png?raw=true)
6. Lalu buka table dan pilih Vista free dan cari file vista free yang sudah di download sebelumnya
![Screenshot 2024-10-13 201918.png](https://github.com/SyahrulWijaya/Dumping-and-Cracking-SAM-Hashes-to-Extract-Plaintext-Passwords/blob/main/Screenshot%202024-10-13%20201918.png?raw=true)
![Screenshot 2024-10-13 202629.png](https://github.com/SyahrulWijaya/Dumping-and-Cracking-SAM-Hashes-to-Extract-Plaintext-Passwords/blob/main/Screenshot%202024-10-13%20202629.png?raw=true)
7. Lalu klik crack dan tunggu hingga proses brute force selesai
![Screenshot 2024-10-13 202737.png](https://github.com/SyahrulWijaya/Dumping-and-Cracking-SAM-Hashes-to-Extract-Plaintext-Passwords/blob/main/Screenshot%202024-10-13%20202737.png?raw=true)
![Screenshot 2024-10-13 210318.png](https://github.com/SyahrulWijaya/Dumping-and-Cracking-SAM-Hashes-to-Extract-Plaintext-Passwords/blob/main/Screenshot%202024-10-13%20210318.png?raw=true)

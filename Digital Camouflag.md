We need to gain access to some routers. Let's try and see if we can find the password in the captured network data: data.pcap.

Hint:
- It looks like someone logged in with their password earlier. Where would log in data be located in a network capture?
- If you think you found the flag, but it doesn't work, consider that the data may be encrypted

Solution:
Buka file data.pcap dengan menggunakan wireshark
Cari data HTML form dari data.pcap
Nilai value adalah perkiraan flagnya
value: UjZBS05oV3dvNw==
Lihat Hint ke 2, flagnya di encrypt
Gunakan base64

Flag: R6AKNhWwo7

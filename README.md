# metasploitfixx





1. Paket metasploit Memasang, dengan memasukan kode:

pkg install unstable-repo

Cara Menggunakan Termux untuk Menengah, Bagian 8: Cara Terbaru Memasang Metasploit di TERMUX, Tanpa ROOT & ERROR

pkg instal metasploit
Cara Menggunakan Termux untuk Menengah, Bagian 8: Cara Terbaru Memasang Metasploit di TERMUX, Tanpa ROOT & ERROR

2. Instal ulang paket ruby, dengan memasukan kode:

pkg install - install ruby

Cara Menggunakan Termux untuk Menengah, Bagian 8: Cara Terbaru Memasang Metasploit di TERMUX, Tanpa ROOT & ERROR

3. Memasang permata bigdecimal, dengan memasukan kode:

permata install bigdecimal -v 1.4.3

Cara Menggunakan Termux untuk Menengah, Bagian 8: Cara Terbaru Memasang Metasploit di TERMUX, Tanpa ROOT & ERROR

4. Mengekspor variabel LD_PRELOAD, dengan memasukan kode:

export LD_PRELOAD = $ LD_PRELOAD: $ PREFIX / lib / ruby ​​/ permata / 2.6.0 / permata / bigdecimal-1.4.3 / ext / bigdecimal / bigdecimal.so



Dan menyetujui LD_PRELOAD sudah selesai di ekspor, maka sobat bisa mengaktifkan msfconsole dengan cara membuat sesi baru , lalu mengetikan: 

msfconsole

atau 

./msfconsole

untuk msfvenom bisa mengetikan: 

msfvenom

atau 

./msfvenom


Hasil: good 

Cara Menggunakan Termux untuk Menengah, Bagian 8: Cara Terbaru Memasang Metasploit di TERMUX, Tanpa ROOT & ERROR

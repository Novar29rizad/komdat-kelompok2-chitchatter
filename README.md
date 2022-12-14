# Aplikasi Web "Chitchatter"


## Sekilas Tentang

Chitchatter adalah alat komunikasi gratis (open source (licensed under GPL v2)) yang dirancang dengan mempertimbangkan keamanan dan privasi. 
Dengan open source (licensed under GPL v2), Encrypted (via WebRTC) dan secara Peer-to-peer sehingga dapat digubnakan kapan saja.
Chitchatter juga Serverless, Ephemeral (Pesan tidak disimpan ke disk), Decentralized serta Self-hostable

## Instalasi (Netlify)

- Clone github https://github.com/jeremyckahn/chitchatter.git ke dalam storage pribadi kemudian fork ke github kelompok
- Buka Netlify (Self-Hosting gratis)
- Klik Add new site -> Import an existing project -> Github
- Pilih Repository kelompok untuk di link ke dalam Netlify
- Karena Netlify sudah langsung otomatisasi terhadap project, maka langsung klik Deploy site
- Tunggu sampai progres deploy selesai
- CLI akan berjalan secara otomatis, terlihat dari Deploy Log
- Setelah muncul tulisan Site is live ✨ maka website siap digunakan
- Link website berada di sebelah judul project


## Konfigurasi

Pada Aplikasi Web "Chitchatter" tidak memerlukan setting server tambahan untuk meningkatkan fungsi dan kinerja aplikasi karena ter-enkripsi oleh via WebRTC, selain itu seluruh history dari chat tidak akan tersimpan.


##  Maintenance
Pada Aplikasi Web "Chitchatter" tidak memerlukan/mengharuskan maintenance secara periodik untuk meningkatkan fungsi dan kinerja aplikasi karena history data/chat tidak tersimpan.


## Otomatisasi (opsional)
Skrip shell untuk Aplikasi Web "Chitchatter" telah tersedia, sehingga tidak memerlukan tindakan lebih.


## Cara Pemakaian

- Tampilan aplikasi web
![image](https://user-images.githubusercontent.com/104239245/196624435-43fb377e-7a0c-4339-8cc2-c4f84f2a81e4.png)
![image](https://user-images.githubusercontent.com/104239245/196624701-60283556-fed0-434b-a3d0-23da4e0b9db5.png)

- (Anonymous-Room-Chat)
![image](https://user-images.githubusercontent.com/104239245/196624969-74004f9c-9d41-44f9-9485-96888e32afd1.png)
![image](https://user-images.githubusercontent.com/104239245/196625155-5e4f6b0c-2652-4595-ada6-cdcbdca1736b.png)

- Fungsi-fungsi utama :
1. Menyediakan Anonymous Room-Chat
2. Menyediakan undangan room-chat berbentuk link (invitation link)
3. End-toend enkripsi chat
4. Tema-mode (dark/light)

- Fitur yang disajikan :
* Beberapa peers untuk tiap room (hanya dibatasi oleh jumlah koneksi pengguna oleh browser).
![image](https://user-images.githubusercontent.com/104239245/196728048-619ec0ce-4873-46d1-97fa-2206792b9bf3.png)
* Nomor yang ditampilkan pada pojok kanan atas layar menunjukkan berapa banyak peers yang terhubung.
![image](https://user-images.githubusercontent.com/104239245/196728195-7ada9dc3-6162-43e8-bf52-e8662699b515.png)
* Dukungan markdown melalui react-markdown.
    Termasuk dukungan untuk syntax highlighting of code..
* Dukungan pesan multiline (tahan Shift dan tekan Enter).
* Tema gelap dan terang (Dark/light themes) ![image](https://user-images.githubusercontent.com/104239245/196727880-5ddc25b0-a22d-4ae4-bb7e-85817b0c51a0.png)




## Pembahasan

- Aplikasi Web "**Chitchatter**" sebagai Website Room-Chat menyajikan instant-anonymous-room-chat bagi pengguna yang dapat digunakan dengan mudah dan cepat. Sehingga pengguna tidak perlu menyiapkan memori dan perangkat tertentu. Dengan penggunaan **Netflify** sebagai layanan hosting gratis dan cepat untuk mendeploy Chitchatter, memudahkan pengguna meng-install aplikasi web dan situs web statis.
    - kelebihan : **Chitchatter** merupakan Web-App dengan Peer-to-peer, Serverless,  Ephemeral (Pesan tidak disimpan ke disk), Decentralized serta Self-hostable, sehingga tidak memerlukan proses yang sulit dalam proses instalasi. Layanan hosting **Netflify** menawarkan layanan hosting dan backend tanpa server untuk aplikasi web dan situs web statis, sehingga dalam proses deploy pun menunjang kemudahan **Chitchatter**  
    - kekurangan : Karena bersifat Ephemeral, pesan chat **Chitchatter** tidak akan tersimpan kedalam disk, sehingga tidak terdapat history dari room-chat yang telah dibuat. dalam penggunaan Aplikasi Web pun hanya dibatasi pesan singkat saja, tanpa dapat mengirimkan siaran foto/video/atau media lainnya. Sedangkan kekurangan menggunakan **Netlify** redirect adalah tidak adanya report statistik.
- Layanan yang juga memiliki fungsi aplikasi sejenis dengan **Chitchatter** yakni anonymous chat telegram, yang juga menawarkan Anonymous-Room-Chat bagi penggunanya


## Referensi
* Layanan Hosting Netlify (www.netlify.com)
* Source Code jeremyckahn / chitchatter (https://github.com/jeremyckahn/chitchatter)

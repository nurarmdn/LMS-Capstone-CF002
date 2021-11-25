# LMS-Capstone-CF002
## Nur Asiah Ramdani - CF002 - Capstone Bidang Pendidikan
## LMS LLC <https://llclearn.cf-002.space/>
----------------------------------------------------------------------------------------------------

### Dokumentasi Teknis:
1. Buka <https://portal.azure.com/> yang sudah memiliki subscription, kemudian buat resource group
2. Buka Marketplace lalu tulis moodle dan pilih >Bitnami LMS powered by Moodle™ LMS
![](https://user-images.githubusercontent.com/79042149/143483344-d20fa533-76c6-4642-b65e-0e5a1fdff30b.png)
3. Klik create dan buat VM dengan pengaturan sesuai yang dibutuhkan. Pengaturan yang saya buat:
![](https://user-images.githubusercontent.com/79042149/143485304-14b896c7-7553-45c8-8bb1-5452369d357b.png)
4. Setelah menunggu proses deploy selesai, lakukan koneksi ke dalam Linux melalui SSH
![](https://user-images.githubusercontent.com/79042149/143492758-4c1d0e22-a859-4ebc-9e16-112c6dd40382.png)
5. Tunggu beberapa menit, kemudian telusuri IP yang sudah dibuat
![Screenshot (1377)](https://user-images.githubusercontent.com/79042149/143492807-81b3ea88-8440-4836-a89a-7d60858b51cd.png)
6. Moodle sudah selesai dibuat dan dapat dioperasikan. Untuk tampilan, maka dapat disesuaikan dengan kreatifitas masing-masing.
7. Jika ingin menggunakan tema template, maka buka situs resmi moodle <https://moodle.org/plugins/>
8. lakukan pemasangan template melalui moodle dengan masuk ke bagian Side administration-> Plugins-> Install plugins
9. Tambahkan DNS untuk kemudahan mengakses website. DNS dapat disetting melalui Azure maupun pihak ketiga.


### Hasil Tampilan Website:
Halaman Utama
![](https://user-images.githubusercontent.com/79042149/143491061-de376d86-5562-482f-be4a-2aa18ed58c57.png)
![](https://user-images.githubusercontent.com/79042149/143491064-f78c7cd7-e0a7-4d8f-a409-c214df363176.png)
![](https://user-images.githubusercontent.com/79042149/143491065-ee278078-930e-4c6e-89d8-857610e4e094.png)

Halaman Login
![](https://user-images.githubusercontent.com/79042149/143491088-b3126f7b-3348-4b4e-be93-d86b6fe2448a.png)

Halaman Dashboard User
![](https://user-images.githubusercontent.com/79042149/143491808-8350c25a-3a46-482f-a611-db897a571a6d.png)

Halaman Profil User
![](https://user-images.githubusercontent.com/79042149/143491854-6f4be978-f258-44d6-b6dd-bb5194f5bfee.png)

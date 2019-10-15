# tugasrdm-indexingtool

>>Image-search-engine(Image Indexing)

1. pertama istall git dahulu dengan syntax “sudo apt install git”
![](pictures/im1.png)

2. Clone dahulu dengan syntax : git clone https://github.com/kudeh/image-search-engine.git
![](pictures/im2.png)

3.Lakukan Update. Syntax : sudo apt-get update
![](pictures/im3.png)

4. Lakukan Upgrade. Syntax : sudo apt-get upgrade
![](pictures/im4.png)

5. lalu install python3 dengan syntax :
sudo apt-get install python3-pip
![](pictures/im5.png)

6.Mulai tahapan untuk menjalankan program. Syntax : 
cd image-search-engine/ lalu pip3 install -r requirements.txt untuk menginstall modul Python 
![](pictures/im6.png)

7. ketik cd app selanjutnya jalankan program dengan syntax : python3 index.py --dataset static/images --index index.csv
![](pictures/im7.png)

8. cek hasil dengan menggunakan syntax pico index.csv
![](pictures/im8.png)

9. Buka ./static/images untuk mengubah image anda

>> Swish-e (Text Indexing)

1. Install Swish-e. Syntax : sudo apt-get install swish-e
![](pictures/t1.png)

2. Modifikasi data dengan beberapa sintax, seperti yang terdapat pada screenshot
Masukkan syntax IndexDir ./data dalam tugas.conf
![](pictures/t3.png)

Masukkan isi dalam file.txt seperti beberapa kata
![](pictures/t5.png)

3. untuk menjalankan program text indexing, gunakan syntax : swish-e -c tugas.conf
![](pictures/t6.png)

4. untuk menjalankan program dengan mencari salah satu kata, gunakan syntax : swish-e -w (misal kata : aku)
![](pictures/t8.png)

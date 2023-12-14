# DownPart

Berikut cara menjalankan program nya melalui terminal atau command prompt
1. Pastikan Anda Telah Menginstal Modul requests:
   Sebelum menjalankan skrip ini, pastikan bahwa Anda telah menginstal modul requests. Jika belum, instal dengan perintah
   ```cmd
   pip install requests
   ```

3. Simpan Program Python:
Simpan dalam file dengan ekstensi .py, misalnya download_script.py.

4. Buka Terminal atau Command Prompt:
Buka terminal atau command prompt di direktori tempat Anda menyimpan skrip Python.

5. Jalankan Program dengan Argumen:
Gunakan perintah berikut untuk menjalankan program dengan argumen yang sesuai. Gantilah <source_url> dengan URL sumber file yang ingin Anda unduh.
    ```cmd
    python download_script.py --source <source_url> --numpart <num_parts> --name <file_name>
    ```
    contoh :
    ```cmd
    python download_script.py --source https://example.com/bigfile.zip --numpart 4 --name myfile.zip
    ```
    Ini akan mengunduh file dari URL tersebut dan membaginya menjadi 4 bagian.

    Jika Anda ingin mengunduh tanpa membagi menjadi partisi, Anda dapat menggunakan argumen --parti False:
    ```cmd
    python download_script.py --source https://example.com/bigfile.zip --parti False --name myfile.zip
    ```
    Jika Anda tidak memberikan nama file (--name), program akan mencoba mengambil nama file dari URL.


Dibuat Oleh: Alta Regina Aliyarahmah

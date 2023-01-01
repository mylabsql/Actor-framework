# Actor-framework
Labview .net webview -  inject whatsapp web, tokopedia

Aplikasi ini mengadopsi kode sumber milik 
1. simons : https://forums.ni.com/t5/UI-Interest-Group-Documents/Windows-8-Style-UI-demo/ta-p/3496737
2. ANSCenter : https://github.com/ANSCenter/LcWebView2
3. pedroslopez : https://github.com/pedroslopez/whatsapp-web.js

Terimakasih untuk aplikasi yang dibuat simons,yang merupakan GUI dengan aktor framework berbasis Labview. Kode sumber tersebut sangat bagus, namun memerlukan waktu yang cukup banyak untuk bisa memahami dan menerapkan contoh sederhana project GUI yang menyerupai win8ui.

Setelah serangkaian perubahan dalam penggunaan activeX guna berinteraksi dengan sebuah browser, akhirnya saya menemukan library dan contoh project yang dikembangkan oleh ANScenter. Sehingga memungkinkan kita untuk berinteraksi dengan sebuah browser terkini menggunakan webview2. Dengan library tersebut menjadikan kita bisa memiliki pintu masuk komunikasi labview dengan browser yang mendukung teknologi terkini. Terimakasih untuk kode yang telah dibagikan melalui github.

Secara tidak sengaja saya juga menemukan kode yang sudah banyak didownload milik pedroslopez. Memungkinkan kita untuk berinteraksi dengan sistem whatsapp berbasis web.
Saya ucapakan terimakasih untuk kode yang telah dibagikan juga diGithub.

Melalui ketiga kode sumber yang sangat keren ini saya mencoba untuk menggabungkannya sehingga memungkinkan aplikasi Labview untuk berinteraksi dengan browser berbasis windows. Saya hanya melakukan perubahan kecil, namun memerlukan waktu yang cukup panjang untuk memahaminya. Kode yang saya modifikasi ini saya share disini, dengan harapan bisa bermanfaat untuk siapapun yang memerlukannya.

Meskipun jauh dari sempurna setidaknya kombinasi sederhana ini sudah bisa berjalan.
Dengan menyisipkan script sederhana javascript, akhirnya labview bisa berinteraksi kembali dengan browser modern milik microsoft.

Kode ini didedikasikan untuk pembelajaran, saya tidak bertanggung jawab atas penyalahgunaan, kegagalan dan gagalnya kode pemrograman ini. Penggunaan kode ini menjadi tanggung jawab anda sendiri.

Salam,


Mylabsql


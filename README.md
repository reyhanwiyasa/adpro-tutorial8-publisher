# adpro-tutorial8-publisher

a. How many data your publlsher program will send to the message broker in one run?
Jawab:
Karena pad publisher, maka dilakukan publish_event sebanyak 5 kali.

b. The url of: “amqp://guest:guest@localhost:5672” is the same as in the subscriber program, what does it mean?
Jawab:
Kedua url sama karena keduanya mengirimkan request yang sama kepada server rabbitMQ. Perbedaannya adalah adalah hasil request ini akan membuat publisher untuk mengirimkan message ke queue. Sedangkan subscriber mengambil data dari message queue dengan dibuatnya sebbuah lsitener.

Foto:
![image](https://github.com/reyhanwiyasa/adpro-tutorial8-publisher/assets/119433464/66c41338-7f36-4f9e-a88e-29974832b5be)
![image](https://github.com/reyhanwiyasa/adpro-tutorial8-publisher/assets/119433464/0ebebbea-7c10-4408-a25b-3fd081ea46e5)
![image](https://github.com/reyhanwiyasa/adpro-tutorial8-publisher/assets/119433464/ae208b32-a76f-45b7-bee1-a26177ef2f43)
Spike terjadi setiap kali adanya dijalankan `cargo run`. Hal ini menunjukan adanya peningkatan message dalam suatu interval waktu.

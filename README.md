# adpro-tutorial8-publisher

a. How many data your publlsher program will send to the message broker in one run?
Jawab:
Karena pad publisher, maka dilakukan publish_event sebanyak 5 kali.

b. The url of: “amqp://guest:guest@localhost:5672” is the same as in the subscriber program, what does it mean?
Jawab:
Kedua url sama karena keduanya mengirimkan request yang sama kepada server rabbitMQ. Perbedaannya adalah adalah hasil request ini akan membuat publisher untuk mengirimkan message ke queue. Sedangkan subscriber mengambil data dari message queue dengan dibuatnya sebbuah lsitener.

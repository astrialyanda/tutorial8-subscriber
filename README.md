**a. what is amqp?** <br>
Amqp atau Advanced message queing protocol adalah standard open layer protocol yang digunakan untuk pertukaran message antar aplikasi. Message akan dikirimkan menggunakan middleware sehingga client akan mendapatkan message melalui middleware tersebut. <br>
<br>
**b. what it means? `guest:guest@localhost:5672` , what is the first quest, and what is the second guest, and what is localhost:5672 is for?** <br>
- `guest:guest@localhost:5672` adalah format address amqp
- `guest:guest` merupakan username dan password agar terautentikasi server. 
- `localhost` menunjukkan host yaitu localhost atau lokal. 
- `5672` adalah nomor port untuk amqp.
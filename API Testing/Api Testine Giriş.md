#🎯 Api Testine Giriş

--

##Clitent & Internet & Server Nedir?
--

- Client: Server'ın bir servisine erişmeye çalışan cihazlar (Genelde kişisel bilgisayarlarımız)

- Internet: Client ile Server arasındaki bağlantı

- Server: Uygulamanın tutulduğu ve Client'lardan gelen isteklere cevap veren yer

--

##Client/Server Architecture
--

- 1-Tier Architecture: File Server ile Computer aynı yerde çalışır.

- 2-Tier Architecture: Computer ile Database ayrı yerlerde direkt bağlılar

- 3-Tier Architecture: Bilgisayar ile Database Application Server (Business Logic Tier)  aracılığıyla birbirine bağlanır

Katmanlar:
1) En Üst Katman: Presentation Layer(Önyüz, Veriyi serverdan alıp sunar)(HTML, JS, CSS)

2) Ara Katman: Application Layer(Business Logic ve Web Server'ın bulunduğu yer)(Java, .NET, C#, Python,C++)

3) En alt katman: Data Layer(Verinin bulunduğu yer)(MySQL, Oracle,PostgreSQL,SQL Server, MangoDB)

Web Uygulamaları Nasıl çalışır?:

Presentation Layerdan Request gelir -> Application Layer Requesti alır ve Data layera gönderilir.-> Data Layer'dan veriye ulaşılır ve response oluşur bu response -> Application Layer'a gider -> Tekrardan en üste çıkarak Presentation Layer'a ulaşır. 


--
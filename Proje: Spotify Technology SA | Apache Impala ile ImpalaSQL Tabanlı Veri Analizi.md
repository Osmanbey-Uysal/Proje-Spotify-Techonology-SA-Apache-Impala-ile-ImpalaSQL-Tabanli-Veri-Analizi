<p align="center">
  <b>Proje</b><br> 
  Spotify Technology SA | Apache Impala ile ImpalaSQL Tabanlı Veri Analizi</b>
</p>

---

<p align="center">
  <b>İş Problemi</b><br>
  İsveç merkezli müzik akışı hizmeti sağlayıcısı Apache Impala ile çeşitli küçük boyutlu analitik sorgulamalar yürütmek istemektedir<br>
  Bu bağlamda Cloudera destekli sanal makinede Apache Impala ve Apache Hadoop aracılığıyla bir benzetim yürütülecektir
</p>
<img width="5296" height="2992" alt="00 Apache Impala" src="https://github.com/user-attachments/assets/81535379-2729-4e6f-881b-56416853ab6c" />

---

<p align="center">
  <b>VERİ SETİ HİKAYESİ</b><br>
  12 DEĞİŞKENDEN VE 8000 GÖZLEMDEN OLUŞMAKTADIR
</p>
<img width="1920" height="1020" alt="0 Veri Seti" src="https://github.com/user-attachments/assets/adad2551-fd4a-4fc9-8763-0d7c5e9eb9a1" />

---

<p align="center">
  <b>1.GÖREV</b><br>
  SANAL MAKİNE ALTYAPI HAZIRLIĞI
</p>
<p align="center">
  <b>1.ADIM</b><br>
  VMWARE WORKSTATION PLAYER 17 İÇERİSİNE CLOUDERA TARAFINDAN GÜÇLENDİRİLMİŞ CENTOS 6.7 İŞLETİM SİSTEMİNİN HAZIR VE APACHE IMPALA İLE APACHE HADOOP ARAÇLARININ KURULU OLDUĞU QUICKSTART SANAL MAKİNE İMAJI KURULDU
</p>
<img width="1920" height="1020" alt="Görev 1 Adım 1" src="https://github.com/user-attachments/assets/7ac25928-e7e1-452e-a5ec-6772db86a7c2" />

---

<p align="center">
  <b>1.GÖREV</b><br>
  SANAL MAKİNE ALTYAPI HAZIRLIĞI
</p>
<p align="center">
  <b>2.ADIM</b><br>
  SANAL MAKİNE İÇİN GEREKLİ OLAN DONANIM KAYNAĞININ DAĞITIMI YAPILDI 
</p>
<img width="1920" height="1020" alt="Görev 1 Adım 2" src="https://github.com/user-attachments/assets/53d79eda-6b7f-4c4b-be96-5f3f974d0bbe" />

---

<p align="center">
  <b>2.GÖREV</b><br>
  VERİ ALTYAPI HAZIRLIĞI
</p>
<p align="center">
  <b>1.ADIM</b><br>
  CASE_STUDY_WITH_IMPALA İSİMLİ HDFS KLASÖRÜ (VERİ TABANI) OLUŞTURULDU
</p>
<img width="5120" height="2876" alt="Görev 2 Adım 1" src="https://github.com/user-attachments/assets/af7c8419-fe65-4de6-85b1-1973531a8e1d" />

---

<p align="center">
  <b>2.GÖREV</b><br>
  VERİ ALTYAPI HAZIRLIĞI
</p>
<p align="center">
  <b>2.ADIM</b><br>
  CSV FORMATLI SPOTIFY_CHURN İSİMLİ VERİ SETİ YÜKLENDİ VE ARDINDAN AYIRICI OLARAK "VİRGÜL" BELİRLENEREK ÖN İZLEME İNCELENDİ
</p>
<img width="5120" height="2876" alt="Görev 2 Adım 2" src="https://github.com/user-attachments/assets/8c779fd8-2164-4c12-903b-cc80159d2718" />

---

<p align="center">
  <b>2.GÖREV</b><br>
  VERİ ALTYAPI HAZIRLIĞI
</p>
<p align="center">
  <b>3.ADIM</b><br>
  SPOTIFY_CHURN İSİMLİ VERİ SETİNİN CASE_STUDY_WITH_IMPALA İSİMLİ HDFS KLASÖRÜ'NE (VERİ TABANI) AKTARIMININ SAĞLANMASININ ARDINDAN FORMAT TÜRÜ "TEXT" OLARAK GÜNCELLENDİ VE DEĞİŞKENLERİN VERİ TÜRLERİ BELİRLENDİ
</p>
<img width="5120" height="2876" alt="Görev 2 Adım 3" src="https://github.com/user-attachments/assets/33c55b32-b11c-42de-998e-6202ee3b64ae" />

---

<p align="center">
  <b>2.GÖREV</b><br>
  VERİ ALTYAPI HAZIRLIĞI
</p>
<p align="center">
  <b>4.ADIM</b><br>
  YAPILAN TÜM İŞLEMLER TAMAMLANDI VE MEVCUT VERİ SETİ TABLO OLARAK ÇALIŞMAYA HAZIR HALE GELDİ
</p>
<img width="5120" height="2876" alt="Görev 2 Adım 4" src="https://github.com/user-attachments/assets/48312f43-a8c5-4d4d-b0a0-2b163b094fc3" />

---

<p align="center">
  <b>3.GÖREV</b><br>
  IMPALASQL TABANLI VERİ ANALİZİ
</p>
<p align="center">
  <b>1.ADIM</b><br>
  OLUŞTURULAN TABLONUN TEPKİ VERİP VERMEYECEĞİNİN TEST EDİLMESİ ADINA TÜM DEĞİŞKENLERİ VE İLK 100 GÖZLEMİ ÇAĞIRACAK SORGU YAZILDI
</p>
<img width="5120" height="2876" alt="Görev 3 Adım 1" src="https://github.com/user-attachments/assets/7f2b2a2d-5c0f-4e0e-9fbc-bd70e4ec04ca" />

---

<p align="center">
  <b>3.GÖREV</b><br>
  IMPALASQL TABANLI VERİ ANALİZİ
</p>
<p align="center">
  <b>2.ADIM</b><br>
  TOPLAM KULLANICI SAYISINI ÇAĞIRACAK SORGU YAZILDI
</p>
<img width="5120" height="2876" alt="Görev 3 Adım 2" src="https://github.com/user-attachments/assets/35a91ce7-a2ab-498c-ba1b-144de3e2fa8e" />

---

<p align="center">
  <b>3.GÖREV</b><br>
  IMPALASQL TABANLI VERİ ANALİZİ
</p>
<p align="center">
  <b>3.ADIM</b><br>
  TOPLAM KADIN KULLANICI SAYISI, TOPLAM ERKEK KULLANICI SAYISI VE TOPLAM DİĞER KULLANICI SAYISINI ÇAĞIRACAK SORGU YAZILDI
</p>
<img width="5120" height="2876" alt="Görev 3 Adım 3" src="https://github.com/user-attachments/assets/3db22944-0854-4dd2-90d6-694b23e9b663" />

---

<p align="center">
  <b>3.GÖREV</b><br>
  IMPALASQL TABANLI VERİ ANALİZİ
</p>
<p align="center">
  <b>4.ADIM</b><br>
  ÜLKELERDEKİ GÜNLÜK ORTALAMA DİNLENEN ŞARKI SAYISINI ÇAĞIRACAK SORGU YAZILDI
</p>
<img width="5120" height="2876" alt="Görev 3 Adım 4" src="https://github.com/user-attachments/assets/b939159e-dbb6-4c36-9a05-343142cc05f9" />

---

<p align="center">
  <b>3.GÖREV</b><br>
  IMPALASQL TABANLI VERİ ANALİZİ
</p>
<p align="center">
  <b>5.ADIM</b><br>
  ÇEVRİMDIŞI ORTAMDA KULLANICILARIN ORTALAMA DİNLEME SÜRESİNİ ÇAĞIRACAK SORGU YAZILDI
</p>
<img width="5120" height="2876" alt="Görev 3 Adım 5" src="https://github.com/user-attachments/assets/1d4e5583-d7cc-4d66-9f53-bd1f233eec3a" />

---

<p align="center">
  <b>3.GÖREV</b><br>
  IMPALASQL TABANLI VERİ ANALİZİ
</p>
<p align="center">
  <b>6.ADIM</b><br>
  30 YAŞ ALTI KULLANICILAR İLE 30 YAŞ ÜSTÜ KULLANICILARIN ORTALAMA DİNLEME SÜRESİNİ ÇAĞIRACAK SORGU YAZILDI
</p>
<img width="5120" height="2876" alt="Görev 3 Adım 6" src="https://github.com/user-attachments/assets/dd011d38-6dab-4deb-814e-6748bfb1a1ef" />

---

<p align="center">
  <b>3.GÖREV</b><br>
  IMPALASQL TABANLI VERİ ANALİZİ
</p>
<p align="center">
  <b>7.ADIM</b><br>
  KULLANICI KİMLİĞİNİ VE HAFTA BAŞINA DİNLENEN TOPLAM REKLAM MİKTARINI BÜYÜKTEN KÜÇÜĞE OLACAK ŞEKİLDE İLK 10 GÖZLEMİ ÇAĞIRACAK SORGU YAZILDI
</p>
<img width="5120" height="2876" alt="Görev 3 Adım 7" src="https://github.com/user-attachments/assets/93ffe7b3-562c-4609-a7e2-89b1314d2b59" />

---

<p align="center">
  <b>3.GÖREV</b><br>
  IMPALASQL TABANLI VERİ ANALİZİ
</p>
<p align="center">
  <b>8.ADIM</b><br>
  ABONELİK TÜRÜ PREMIUM OLUP ABONELİĞİNİ İPTAL EDEN KULLANICILARIN YAŞ ORTALAMASINI ÇAĞIRACAK SORGU YAZILDI
</p>
<img width="5120" height="2876" alt="Görev 3 Adım 8" src="https://github.com/user-attachments/assets/6c845b61-84c4-41bb-8b04-d4b405f330ce" />

---

<p align="center">
  <b>PROJE SAHİBİ</b><br>
  OSMANBEY UYSAL
</p>

---

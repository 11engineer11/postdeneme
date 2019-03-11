# postdeneme
Gerekli kurulumlar:
Python pip(virtualenv ve djangonun indirilmesi icin)
virtualenv(yaptıgımız seylerin orjinal python klasörünü etkilememesi icin)
django(Web catısı)
bunlar indirildikten sonra cmd ile sanal ortamı calıstırıp ardından python manage.py runserver diyerek bir django serverini 127.0.0.1 ve 8000
portunda calıstırmıs oluyoruz. aldıgımız uyarı ile migrate komutunu calıstırıp veritabanını sqlite(admin side) ile olusturuyoruz. ardından createsuperuser ile
bir admin hesabı olusturuyoruz. 

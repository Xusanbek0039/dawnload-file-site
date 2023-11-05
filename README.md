# Dawnload-file-WebSite
Oddiy django loyihasi

Ushbu loyihani ishlab chiqishimdan maqsad elektron kutubxona tashkil. Datadase sqlite3 da
Ushbu loyihani kompyuteringizda qanday ishga tushirish bo'yicha bosqichma-bosqich buyruqlar:


1-qadam)- Muhitni yuklab oling Virtualenv

```
pip install virtualenv
```

2-qadam)- Virtualenv yarating

```
virtualenv venv
```

3-qadam)- Virtual muhitni faollashtirish

```
venv/Scripts/activate
```

4-qadam)- O'rnatish talablari agar kutubxonalar to'liq bo'lsa shart emas!

```
pip install -r requirements.txt
```
Eslatma: Birinchi marta o'rnatish uchun yuqoridagi buyruq talab qilinadi!

5-qadam)- Quyidagi buyruqlarni bajaring bu shart database uchun

```
python manage.py makemigrations
```
```
python manage.py migrate
```
Eslatma: Agar database ni debug da ishga tushursangiz bu majburiy!

6-qadam)- Administratorga kirish uchun createsuperuser yarating va agar yaratilmagan bo'lsa, ko'rsatmalarga rioya qiling:

Username: Xusanbek
Parol: 0071

```
python manage.py createsuperuser
```

7-qadam)- Statik fayllarni bitta joyda to'plang. Bu shart aks holda sayt css fayllarni o'qimaydi
```
python manage.py collectstatic
```
<br>

## Ishga tushurish

```
python manage.py runserver
```
Loyiha ishga tayyor uni ishga tushurish mumkin!
Eslatma: Agar qadamlar to'g'ri bajarilsa loyiha ishga tushadi!

<br>


## Deploy qilingan sayt linki:

# https://ebook-uz.onrender.com
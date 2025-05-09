# Subdomain Finder

Ushbu loyiha Creative Commons Attribution-NoDerivatives 4.0 International (CC BY-ND 4.0) litsenziyasi ostida tarqatiladi. 

Bu loyiha Web saytlarning subdomen larini topishda sizga yordam beradi.

## Muallif UZTERMIN

## Hozircha faqat Linux u-n mavjud :

Siz bu loyihani quyidagi holatlarda ishlatishingiz mumkin:
- Dasturdan foydalanish (ko‘rish, ishlatish).
- Dasturda o‘zgartirishlar kiritish taqiqlanadi.

### [Linux versiyasi](./subdomain-finder)
- Terminalda :
- Avval clone qilib oling git bilan:
```shell
sudo apt install git
git clone https://github.com/uztermin/subdomain-finder.git
```
![image alt](https://github.com/uztermin/subdomain-finder/blob/239bb2d7e29f2cbd7d7fb77143e6c635ea439579/Screenshot%20From%202025-05-09%2009-54-30.png)




- Keyin shu Directory ga o'tib olasiz:
```shell
cd subdomen-finder
```
- Python yordamida venv muhiti yaratib olishingiz kerak:
```shell
python -m venv venv
cd venv
cd bin
source activate
cd ..
cd ..
```
![image alt](https://github.com/uztermin/subdomain-finder/blob/e97b13405d396f1eef9a86e2f224478dfc872c73/Screenshot%20From%202025-05-09%2009-56-40.png)





- Endi kerakli kutubxonalarni install qilib olishingiz zarur:
```shell
pip install -r requirements.txt 
```
- yoki
```shell
pip3 install -r requirements.txt
```
- Va Kodni ishga tushrishingiz mumkin:
```shell
python3 linux-subdomen.py
```

## Mualliflik huquqi

Muallif: [uztermin](https://github.com/uztermin)  
Litsenziya: Creative Commons Attribution-NoDerivatives 4.0 International (CC BY-ND 4.0)

Barcha foydalanishda mualliflik huquqi saqlanadi va sizning foydalanishingizda yuqoridagi litsenziya matni ko‘rsatilishi kerak.

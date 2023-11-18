PYTHON
Python dilinde kod yazma :	#!/usr/bin/env python
Türkçe karakter desteği :	# -*- coding: utf-8 -*-
base64 decoder :	for word in $(cat şifre.txt);do echo $word | base64 --decode >> çıktı.txt; done
Komut satırında çalışmak için :
import os  	 //Komut satırında çalışmak için os ekledik
os.system(“apt-get install figlet”)	//figlet büyük yazı yazdırma aracı
os.system(“clear”)
os.system(“figlet mac değiştirme”)
Ekrana yazı yazdırmak :	print(“””üç tırnak arasına ekranda görmek istediğini yaz”””)
Seçenekler arasından seçim yapmak :
islemno = raw_input (“İşlem no girin”)
if (islemno==”1”):
hedef ip =raw_input(“hedef ip girin:”)
os.system(”nmap” + hedef ip)
elif (islemno==”2”):
hedef ip =raw_input(“hedef ip girin:”)
os.system(”nmap -sS -sV” + hedef ip)
else: print(“hatalı seçim”)

CTRL + K + C	=	Toplu yorum satırına alma
CTRL + K + U	=	Toplu yorum satırını kaldırma

Scapy

ARP Poison
ARP Request paketi	=  scapy.ARP(op=1) (Default)
ARP Response paketi	=  
degisken = scapy.ARP(op=2,pdst=hedef ip, hwdst=hedef mac, psrc= modem ip gir)
scapy.send(degisken)  :  Paketi gönderir.
hwdst	= Hedef mac adresi
pdst	= Hedef ip adresi
psrc	= Kaynak ip adresi
hwsrc	= Kaynak mac adresi

Python Kodunu Exe Yapma

"C:\Users\TR\AppData\Local\Programs\Python\Python310\Scripts\pyinstaller.exe" MyPackage.py --onefile --add-data "C:\Users\TR\Desktop\adobe.pdf;." --noconsole --icon C:\Users\TR\Desktop\pdf.ico

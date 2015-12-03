# fingil
برای حل مشکل اشتباه تایپ کردن به دلیل تنظیم نبودن زبان کیبرد میتوانید از این اسکریپت کمک بگیرید
##پیش نیازهای نصب
قبل از نصب مطمئن شوید که همه بسته های پیش نیاز نصب هستند. برای توزیع های بر اساس دبیان مانند اوبونتو و مینت و ...

	$ sudo apt-get install xclip xdotool

برای توزیع های بر اساس آرچ

	$ sudo pacman -s xclip xdotool

برای توزیع های بر اساس فدورا

	$ sudo dnf install xclip xdotool

برای نصب اسکریپت از این کدها استفاده کنید

	$ cd
	$ cd /tmp
	$ wget -O fingil.tar.gz https://github.com/alireza-amirsamimi/pdmt/archive/master.tar.gz
	$ tar  --overwrite --overwrite-dir -xf fingil.tar.gz
	$ chmod +x /tmp/fingil-master/fingil
	$ sudo  mv -f /tmp/fingil-master/fingil /usr/bin

برای خارج کردن نصب
	$ sudo rm -r /usr/bin/fingil

## Contact me
Me on twiter:
https://twitter.com/AR_AmirSamimi

My weblog:
http://amirsamimi.mihanblog.com

My email adress:
alireza.amirsamimi@ubuntu.ir


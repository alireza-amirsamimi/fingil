# Fingil
برای حل مشکل اشتباه تایپ کردن به دلیل تنظیم نبودن زبان کیبرد میتوانید از این اسکریپت کمک بگیرید. مثلا وقتی به جای کلمه

 google

 کلمه لخخلمث 
را مینویسید. یا به جای سلام کلمه

 sghl

را مینویسید با این برنامه به راحتی میتوانید مشکل را حل کنید.
![ScreenShot](http://s3.picofile.com/file/8226246300/optimised2.gif)
##پیش نیازهای نصب
قبل از نصب مطمئن شوید که همه بسته های پیش نیاز نصب هستند. برای توزیع های بر اساس دبیان مانند اوبونتو و مینت و ...

	$ sudo apt-get install xclip xdotool

برای توزیع های بر اساس آرچ

	$ sudo pacman -s xclip xdotool

برای توزیع های بر اساس فدورا

	$ sudo dnf install xclip xdotool

##برای نصب اسکریپت از این کدها استفاده کنید

	$ cd
	$ cd /tmp
	$ wget -O fingil.tar.gz https://github.com/alireza-amirsamimi/fingil/archive/master.tar.gz
	$ tar  --overwrite --overwrite-dir -xf fingil.tar.gz
	$ chmod +x /tmp/fingil-master/fingil
	$ sudo  mv -f /tmp/fingil-master/fingil /usr/bin

##برای خارج کردن نصب


	$ sudo rm -r /usr/bin/fingil
##بعد از نصب
بعد از اینکه برنامه نصب شد کافی است با توجه به میزکار خود یک شرتکات برای دستور

 $ fingil

 بسازید ، مثلا کلیدهای 

 shift+ctrl+j

 و بعد برای استفاده
متنی را که اشتباه تایپ کرده اید هایلایت کنید و کپی کنید و با شرتکات کیبرد فینگیل! را اجرا کنید.
## Contact me
Me on twiter:
https://twitter.com/AR_AmirSamimi

My weblog:
http://amirsamimi.mihanblog.com

My email adress:
alireza.amirsamimi@ubuntu.ir


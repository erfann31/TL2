# languagesTheory_2
این پروژه شامل چندین بخش زیر است:
##Machin
![Untitled](https://user-images.githubusercontent.com/75057732/173904078-ef94cb8c-f0b3-4b33-b7ac-6c94213d1f41.jpg)
##Grammer
our grammar from machine is:
A#0A|1B
B#0A|1C
C#DE
D#KKKK
E#0C|1F|qB
F#0C|1G
G#1H|qB
H#1I|0H|qB
I#1J
J#dB
K#1|0
##Regular-expression
our regular expression from grammar is:0*1(00*1)*1(0+1)(1+0)(1+0)(0+1)((q(00*1)*1+0)(0+1)(1+0)(1+0)(0+1))*1(0(0+1)(1+0)(1+0)(0+1)((q(00*1)*1+0)(0+1)(1+0)(1+0)(0+1))*1)*1(q(00*1)*1(0+1)(1+0)(1+0)(0+1)((q(00*1)*1+0)(0+1)(1+0)(1+0)(0+1))*1(0(0+1)(1+0)(1+0)(0+1)((q(00*1)*1+0)(0+1)(1+0)(1+0)(0+1))*1)*1)*1(q(00*1)*1(0+1)(1+0)(1+0)(0+1)((q(00*1)*1+0)(0+1)(1+0)(1+0)(0+1))*1(0(0+1)(1+0)(1+0)(0+1)((q(00*1)*1+0)(0+1)(1+0)(1+0)(0+1))*1)*1(q(00*1)*1(0+1)(1+0)(1+0)(0+1)((q(00*1)*1+0)(0+1)(1+0)(1+0)(0+1))*1(0(0+1)(1+0)(1+0)(0+1)((q(00*1)*1+0)(0+1)(1+0)(1+0)(0+1))*1)*1)*1+0)*11(d(00*1)*1(0+1)(1+0)(1+0)(0+1)((q(00*1)*1+0)(0+1)(1+0)(1+0)(0+1))*1(0(0+1)(1+0)(1+0)(0+1)((q(00*1)*1+0)(0+1)(1+0)(1+0)(0+1))*1)*1(q(00*1)*1(0+1)(1+0)(1+0)(0+1)((q(00*1)*1+0)(0+1)(1+0)(1+0)(0+1))*1(0(0+1)(1+0)(1+0)(0+1)((q(00*1)*1+0)(0+1)(1+0)(1+0)(0+1))*1)*1)*1(q(00*1)*1(0+1)(1+0)(1+0)(0+1)((q(00*1)*1+0)(0+1)(1+0)(1+0)(0+1))*1(0(0+1)(1+0)(1+0)(0+1)((q(00*1)*1+0)(0+1)(1+0)(1+0)(0+1))*1)*1(q(00*1)*1(0+1)(1+0)(1+0)(0+1)((q(00*1)*1+0)(0+1)(1+0)(1+0)(0+1))*1(0(0+1)(1+0)(1+0)(0+1)((q(00*1)*1+0)(0+1)(1+0)(1+0)(0+1))*1)*1)*1+0)*11)*d(00*1)*1(0+1)(1+0)(1+0)(0+1)((q(00*1)*1+0)(0+1)(1+0)(1+0)(0+1))*1(0(0+1)(1+0)(1+0)(0+1)((q(00*1)*1+0)(0+1)(1+0)(1+0)(0+1))*1)*1(q(00*1)*1(0+1)(1+0)(1+0)(0+1)((q(00*1)*1+0)(0+1)(1+0)(1+0)(0+1))*1(0(0+1)(1+0)(1+0)(0+1)((q(00*1)*1+0)(0+1)(1+0)(1+0)(0+1))*1)*1)*1(q(00*1)*1(0+1)(1+0)(1+0)(0+1)((q(00*1)*1+0)(0+1)(1+0)(1+0)(0+1))*1(0(0+1)(1+0)(1+0)(0+1)((q(00*1)*1+0)(0+1)(1+0)(1+0)(0+1))*1)*1(q(00*1)*1(0+1)(1+0)(1+0)(0+1)((q(00*1)*1+0)(0+1)(1+0)(1+0)(0+1))*1(0(0+1)(1+0)(1+0)(0+1)((q(00*1)*1+0)(0+1)(1+0)(1+0)(0+1))*1)*1)*1+0)*q(00*1)*1(0+1)(1+0)(1+0)(0+1)((q(00*1)*1+0)(0+1)(1+0)(1+0)(0+1))*1(0(0+1)(1+0)(1+0)(0+1)((q(00*1)*1+0)(0+1)(1+0)(1+0)(0+1))*1)*1(q(00*1)*1(0+1)(1+0)(1+0)(0+1)((q(00*1)*1+0)(0+1)(1+0)(1+0)(0+1))*1(0(0+1)(1+0)(1+0)(0+1)((q(00*1)*1+0)(0+1)(1+0)(1+0)(0+1))*1)*1)*q(00*1)*1(0+1)(1+0)(1+0)(0+1)((q(00*1)*1+0)(0+1)(1+0)(1+0)(0+1))*1(0(0+1)(1+0)(1+0)(0+1)((q(00*1)*1+0)(0+1)(1+0)(1+0)(0+1))*1)*0(0+1)(1+0)(1+0)(0+1)((q(00*1)*1+0)(0+1)(1+0)(1+0)(0+1))*q(00*1)*+q(00*1)*1(0+1)(1+0)(1+0)(0+1)((q(00*1)*1+0)(0+1)(1+0)(1+0)(0+1))*q(00*1)*+q(00*1)*+q(00*1)*1(0+1)(1+0)(1+0)(0+1)((q(00*1)*1+0)(0+1)(1+0)(1+0)(0+1))*1(0(0+1)(1+0)(1+0)(0+1)((q(00*1)*1+0)(0+1)(1+0)(1+0)(0+1))*1)*0(0+1)(1+0)(1+0)(0+1)((q(00*1)*1+0)(0+1)(1+0)(1+0)(0+1))*q(00*1)*+q(00*1)*1(0+1)(1+0)(1+0)(0+1)((q(00*1)*1+0)(0+1)(1+0)(1+0)(0+1))*q(00*1)*+q(00*1)*+d(00*1)*1(0+1)(1+0)(1+0)(0+1)((q(00*1)*1+0)(0+1)(1+0)(1+0)(0+1))*1(0(0+1)(1+0)(1+0)(0+1)((q(00*1)*1+0)(0+1)(1+0)(1+0)(0+1))*1)*1(q(00*1)*1(0+1)(1+0)(1+0)(0+1)((q(00*1)*1+0)(0+1)(1+0)(1+0)(0+1))*1(0(0+1)(1+0)(1+0)(0+1)((q(00*1)*1+0)(0+1)(1+0)(1+0)(0+1))*1)*1)*q(00*1)*1(0+1)(1+0)(1+0)(0+1)((q(00*1)*1+0)(0+1)(1+0)(1+0)(0+1))*1(0(0+1)(1+0)(1+0)(0+1)((q(00*1)*1+0)(0+1)(1+0)(1+0)(0+1))*1)*0(0+1)(1+0)(1+0)(0+1)((q(00*1)*1+0)(0+1)(1+0)(1+0)(0+1))*q(00*1)*+q(00*1)*1(0+1)(1+0)(1+0)(0+1)((q(00*1)*1+0)(0+1)(1+0)(1+0)(0+1))*q(00*1)*+q(00*1)*+d(00*1)*1(0+1)(1+0)(1+0)(0+1)((q(00*1)*1+0)(0+1)(1+0)(1+0)(0+1))*1(0(0+1)(1+0)(1+0)(0+1)((q(00*1)*1+0)(0+1)(1+0)(1+0)(0+1))*1)*0(0+1)(1+0)(1+0)(0+1)((q(00*1)*1+0)(0+1)(1+0)(1+0)(0+1))*q(00*1)*+d(00*1)*1(0+1)(1+0)(1+0)(0+1)((q(00*1)*1+0)(0+1)(1+0)(1+0)(0+1))*q(00*1)*+d(00*1)*+0*1(00*1)*1(0+1)(1+0)(1+0)(0+1)((q(00*1)*1+0)(0+1)(1+0)(1+0)(0+1))*1(0(0+1)(1+0)(1+0)(0+1)((q(00*1)*1+0)(0+1)(1+0)(1+0)(0+1))*1)*1(q(00*1)*1(0+1)(1+0)(1+0)(0+1)((q(00*1)*1+0)(0+1)(1+0)(1+0)(0+1))*1(0(0+1)(1+0)(1+0)(0+1)((q(00*1)*1+0)(0+1)(1+0)(1+0)(0+1))*1)*1)*1(q(00*1)*1(0+1)(1+0)(1+0)(0+1)((q(00*1)*1+0)(0+1)(1+0)(1+0)(0+1))*1(0(0+1)(1+0)(1+0)(0+1)((q(00*1)*1+0)(0+1)(1+0)(1+0)(0+1))*1)*1(q(00*1)*1(0+1)(1+0)(1+0)(0+1)((q(00*1)*1+0)(0+1)(1+0)(1+0)(0+1))*1(0(0+1)(1+0)(1+0)(0+1)((q(00*1)*1+0)(0+1)(1+0)(1+0)(0+1))*1)*1)*1+0)*q(00*1)*1(0+1)(1+0)(1+0)(0+1)((q(00*1)*1+0)(0+1)(1+0)(1+0)(0+1))*1(0(0+1)(1+0)(1+0)(0+1)((q(00*1)*1+0)(0+1)(1+0)(1+0)(0+1))*1)*1(q(00*1)*1(0+1)(1+0)(1+0)(0+1)((q(00*1)*1+0)(0+1)(1+0)(1+0)(0+1))*1(0(0+1)(1+0)(1+0)(0+1)((q(00*1)*1+0)(0+1)(1+0)(1+0)(0+1))*1)*1)*q(00*1)*1(0+1)(1+0)(1+0)(0+1)((q(00*1)*1+0)(0+1)(1+0)(1+0)(0+1))*1(0(0+1)(1+0)(1+0)(0+1)((q(00*1)*1+0)(0+1)(1+0)(1+0)(0+1))*1)*0(0+1)(1+0)(1+0)(0+1)((q(00*1)*1+0)(0+1)(1+0)(1+0)(0+1))*q(00*1)*+q(00*1)*1(0+1)(1+0)(1+0)(0+1)((q(00*1)*1+0)(0+1)(1+0)(1+0)(0+1))*q(00*1)*+q(00*1)*+q(00*1)*1(0+1)(1+0)(1+0)(0+1)((q(00*1)*1+0)(0+1)(1+0)(1+0)(0+1))*1(0(0+1)(1+0)(1+0)(0+1)((q(00*1)*1+0)(0+1)(1+0)(1+0)(0+1))*1)*0(0+1)(1+0)(1+0)(0+1)((q(00*1)*1+0)(0+1)(1+0)(1+0)(0+1))*q(00*1)*+q(00*1)*1(0+1)(1+0)(1+0)(0+1)((q(00*1)*1+0)(0+1)(1+0)(1+0)(0+1))*q(00*1)*+q(00*1)*+0*1(00*1)*1(0+1)(1+0)(1+0)(0+1)((q(00*1)*1+0)(0+1)(1+0)(1+0)(0+1))*1(0(0+1)(1+0)(1+0)(0+1)((q(00*1)*1+0)(0+1)(1+0)(1+0)(0+1))*1)*1(q(00*1)*1(0+1)(1+0)(1+0)(0+1)((q(00*1)*1+0)(0+1)(1+0)(1+0)(0+1))*1(0(0+1)(1+0)(1+0)(0+1)((q(00*1)*1+0)(0+1)(1+0)(1+0)(0+1))*1)*1)*q(00*1)*1(0+1)(1+0)(1+0)(0+1)((q(00*1)*1+0)(0+1)(1+0)(1+0)(0+1))*1(0(0+1)(1+0)(1+0)(0+1)((q(00*1)*1+0)(0+1)(1+0)(1+0)(0+1))*1)*0(0+1)(1+0)(1+0)(0+1)((q(00*1)*1+0)(0+1)(1+0)(1+0)(0+1))*q(00*1)*+q(00*1)*1(0+1)(1+0)(1+0)(0+1)((q(00*1)*1+0)(0+1)(1+0)(1+0)(0+1))*q(00*1)*+q(00*1)*+0*1(00*1)*1(0+1)(1+0)(1+0)(0+1)((q(00*1)*1+0)(0+1)(1+0)(1+0)(0+1))*1(0(0+1)(1+0)(1+0)(0+1)((q(00*1)*1+0)(0+1)(1+0)(1+0)(0+1))*1)*0(0+1)(1+0)(1+0)(0+1)((q(00*1)*1+0)(0+1)(1+0)(1+0)(0+1))*q(00*1)*+0*1(00*1)*1(0+1)(1+0)(1+0)(0+1)((q(00*1)*1+0)(0+1)(1+0)(1+0)(0+1))*q(00*1)*+0*1(00*1)*
##User interface
این بخش هم از روی شکل ماشین انجام شد و منو های خرید و انتخاب محصول پیاده سازی شد به این شکل که فایلی حاوی محتویات ماشین به برنامه داده میشود و سیستم بعد از ساختن لیست محصولات منو ی خرید را نمایش میدهد پس از فشردن دکمه خرید و انتخاب محصول و تایید موجودی چک میشود و وارد عملیات پرداخت میشود اگر پرداخت با موفقیت انجام شد تک محصول تحویل داده میشود. مدل دستگاه را در پایین میبینید.
![image](https://user-images.githubusercontent.com/75057732/173906440-dfb70403-a3e0-4fd0-9a0a-50329aa98289.png)
![image](https://user-images.githubusercontent.com/75057732/173906562-c341ffe5-bc64-4ee1-bc8d-7e11e6bb460c.png)
##Generate machine code
کد دستگاه طبق شکل ماشین که قبلا دیدیم تولید میشود.
##Code for derivation of machine code from regular expression
برای این بخش ما یک فایل شامل تارخچه ماشین را خوانده و بعد از هربار خاموش شدن دستگاه تاریخچه را بروز رسانی میکند که اینکار توسط فیلتری اجرا میشود که با مدل کردن dfa ماشین انجام شده است.

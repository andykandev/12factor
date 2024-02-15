<style>*{direction: rtl}</style>
پیشینه
==========

مشارکت ‌کنندگان این سند مستقیماً در توسعه و استقرار صدها برنامه مشارکت داشته‌اند و از طریق کار ما در [هیکورو](https://www.heroku.com/)، به ‌طور غیرمستقیم شاهد توسعه، عملکرد و رشد صدها هزار برنامه بوده اند.

این سند تمام تجربیات و مشاهدات ما را در مورد طیف گسترده ای از برنامه های نرم افزاری به عنوان سرویس در طبیعت ترکیب می کند. این مثلثی است بر روی شیوه‌های ایده‌آل برای توسعه برنامه، توجه ویژه به پویایی رشد ارگانیک یک برنامه در طول زمان، پویایی همکاری بین توسعه‌دهندگانی که روی پایگاه کد برنامه کار می‌کنند، و **جلوگیری از هزینه‌های فرسایش نرم‌افزار**.

This document synthesizes all of our experience and observations on a wide variety of software-as-a-service apps in the wild.  It is a triangulation on ideal practices for app development, paying particular attention to the dynamics of the organic growth of an app over time, the dynamics of collaboration between developers working on the app's codebase, and <a href="http://blog.heroku.com/archives/2011/6/28/the_new_heroku_4_erosion_resistance_explicit_contracts/" target="_blank">avoiding the cost of software erosion</a>.

انگیزه ما افزایش آگاهی از برخی مشکلات سیستمی است که در توسعه برنامه های کاربردی مدرن دیده ایم، واژگان مشترکی برای بحث در مورد آن مشکلات ارائه می دهیم، و مجموعه ای از راه حل های مفهومی گسترده برای آن مشکلات را با اصطلاحات همراه ارائه می دهیم. این قالب از کتاب‌های مارتین فاولر ** و *بازساخت کد* الهام گرفته شده است.

Our motivation is to raise awareness of some systemic problems we've seen in modern application development, to provide a shared vocabulary for discussing those problems, and to offer a set of broad conceptual solutions to those problems with accompanying terminology.  The format is inspired by Martin Fowler's books *<a href="https://books.google.com/books/about/Patterns_of_enterprise_application_archi.html?id=FyWZt5DdvFkC" target="_blank">Patterns of Enterprise Application Architecture</a>* and *<a href="https://books.google.com/books/about/Refactoring.html?id=1MsETFPD3I0C" target="_blank">Refactoring</a>*.


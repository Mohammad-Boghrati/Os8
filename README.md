Chmod 397: اعداد 0 تا 7 فقط در بازه دستورات هستند

Chmod 440: برای کاربر و گروه فقط دسترسی خواندن اجرا میکند و همه دسترسی هارا از سایرین میگیرد.

Chmod a=rx TestFile:این دستور به همه (یوزر و گروه و سایر افراد) دسترسی فقط دسترسی خواندن و اجرا کردن را میدهد

Chmod g=w TestFile: این دستور به گروه اجازه فقط دسترسی به نوشتن را میدهد

Chmod r+x TestFile:این دستور اجرا نمیشود و نا معتبر است.

Chmod u+g TestFile:این دستور سطح دسترسی را ثابت نگه داشت و در آن تغییری ایجاد نکرد

Chmod -v: تغییرات سطح دسترسی را نمایش میدهد

Chmod -R:بصورت بازگشتی سطح دسترسی هارا تغییر میدهد

Chmod -c:مانند مورد اول تغییرات انجام شده در دسترسی های فایل مورد نظر را نشان میدهد با این تفاوت که اگر تغییراتی نباشد پیامی نشان داده نمیشود
* * *

## دستورات سودو

| دستور | درباره دستور |
|:--------|:-------------------------------------------|
|🔻Brodcast Option🔻|
|🔷!pm [Id] [Text]  |ارسال پیام به ایدی موردنظر|
|🔶!bcpv [text] | ارسال پیغام همگانی به پیوی |
|🔷!bcgp [text] | ارسال پیغام همگانی به گروها |
|🔶!bcsgp [text] | ارسال پیغام همگانی به سوپرگروها |
|🔷!bc [text] | ارسال پیغام همگانی|
|🔶!fwdall {reply on msg} | فوروارد همگانی |
|🔷!fwdpv {reply on msg} | فوروارد همگانی به پیوی|
|🔶!fwdagp {reply on msg} | فوروارد همگانی به گروها|
|🔷!fwdasgp {reply on msg} | فوروارد همگانی به سوپرگروها |
|🔻User Option🔻|
|🔶!block [Id] | بلاک کردن فرد مورد نظر |
|🔷!unblock [id] | انبلاک کردن فرد مور نظر |
|🔻Contacts Option🔻|
|🔶!addcontact [phone] [FirstName][LastName] | اضافه کردن یک کانتکت |
|🔷!delcontact [phone] [FirstName][LastName] | حذف کردن یک کانتکت |
|🔶!sendcontact [phone] [FirstName][LastName] | ارسال یک کانتکت |
|🔷!contactlist | دریافت لیست کانتکت ها |
|🔻Robot Advanced Option🔻|
|🔶!markread [on]/[off] | روشن و خاموش کردن تیک مارک رید |
|🔷!setphoto {on reply photo} | ست کردن پروفایل ربات |
|🔶!stats | دریافت آمار ربات |
|🔷!addmember | اضافه کردن کانتکت های ربات به گروه |
|🔶!echo [text] | برگرداندن نوشته |
|🔷!export link | دریافت لینک های ذخیره شده |
|🔶!settext [text] | تنظیم پیام ادشدن کانتکت |
|🔷!text | نمایش پیام ذخیره شده اد کانتکت |
|🔶!reload| ریلود کردن ربات |
|🔷!addsudo [id]| اضافه کردن سودو به ربات |
|🔶!remsudo [id]| حذف کردن سودو ربات |
|🔷!serverinfo| نمایش وضعیت سرور |
|🔶!reset stats|ریست کردن آمار تبچی|
|🔷!leave| لفت دادن ربات از گروه|
|🔶!leave [id] |لفت دادن تبچی از گروهی که گفته شده|
|🔷!addtoall [id] |اد کردن فرد مورد نظر به گروهای موردنظر|
|🔶!autojoin [on][off] |فعال کردن اتوجوین|
|🔷!addedmsg [on][off] |فعال کردن پیام  ادشدی پیوی|
|🔶!addcontacts [on][off] |فعال کردن اد شدن اکانت|
|🔷!settings |نمایش تنظیمات|
|🔶 $cmd | اجرا کردن دستور در ترمینال |

* * *

# 🔳 نصب 🔳

```sh
# دستورات نصب

#نصب پیش نیازها

sudo apt-get install libreadline-dev libconfig-dev libssl-dev lua5.2 liblua5.2-dev lua-socket lua-sec lua-expat libevent-dev make unzip git redis-server autoconf g++ libjansson-dev libpython-dev expat libexpat1-dev

#کد نصب بوت
cd $HOME
git clone https://github.com/tabchis/tabadol.git
cd Tabchi
./launch.sh

```

## 💢 دستورات اتولانچ 💢
```sh
sudo killall screen
sudo killall tmux
sudo killall telegram-cli
sudo tmux new-session -s script "bash steady.sh -t"
```

# Learn AJAX in 1 minute. ([English Version!] (http://github.com))

## AJAX چیست؟
AJAX (ایجکس) مخفف عبارت Asynchronous JavaScript and XML و به معنای  ترکیب جاوا اسکریپت و xml‌ غیرهمزمان و ناهمگام است. آشنایی با این تکنولوژی پرکاربرد برای توسعه دهندگان و طراحان ضروری است. 

## از زبان من 
AJAX بهتون این اجازرو میده بدون رفرش کردن پیج یا لینک شدن به جای دیگه دیتا رو به صفحتون اضافه کنید!

## چجوری میشه نوشتش؟

`
var request = new XMLHttpRequest() // این خط ی آبجکت XML میسازه

request.open("GET","file.txt") // تو این خط ما درخواستمون رو تعریف میکنیم
request.onreadystatechange = () => { // این خط ایونت هارو هندل میکنه
    if(request.state === 200 && request.readyState === 4) { // اگر سرور با موفقیت به درخواستمون جواب داد ادامه بده
        console.log("inja mitonin harchi mikhain add konin to karatono anjam bede :D.")
    }
}

request.send() // و در آخر هم ارسال درخواست به سرور

`

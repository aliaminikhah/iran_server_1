# iran_server_1
- نمایش کلاینت ایدی
- نمایش نام اکانت  اصلی
- چت خصوصی


```
import urllib.request, _babase, os

url = "https://raw.githubusercontent.com/aliaminikhah/iran_server_1/main/iran_server_1.py"
path = os.path.join(
    _babase.env()["python_directory_user"],
    "iran_server_1.py",
)

urllib.request.urlretrieve(url, path)
print("پلاگین نصب شد؛ بازی را کامل ببند و دوباره باز کن.")
```

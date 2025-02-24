Pipe Network Devnet Node 2.8 +

### به‌روز‌رسانی سیستم

```
sudo apt update && sudo apt upgrade -y
```

### نصب curl (در صورت نیاز):

```
sudo apt install curl -y
```

### دانلود فایل باینری

```
curl -L -o pop "https://dl.pipecdn.app/v0.2.8/pop"
```

### اعطای دسترسی اجرایی به فایل دانلود شده:

```
chmod +x pop
```

### ایجاد پوشه برای کش دانلود:

```
mkdir download_cache
```

### اجرای سریع (Quick Start)

```
sudo ./pop --signup-by-referral-route d236978702e5d355
```

### مشاهده وضعیت و آمار نود:
```
./pop --status
```
### به‌روزرسانی نود:
```
./pop --refresh
```
### پشتیبان‌گیری از فایل node_info.json:
متن داخل فایل رو کپی کنید و ذخیره کنید یه جای امن ، مهمه!
```
nano node_info.json
```
### راهنمای کامل نود 
```
./pop --help
```

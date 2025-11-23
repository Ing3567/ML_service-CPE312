## Lab ML_service in CPE312
Model as a Service by Flask and Docker

---

## SET UP

---

install libarary
run in powershell
python
```
pip install -r requirements.txt
```
Docker
```
cd D:\CPE312\ml_service
docker build -t ds-ml-service .
```

## Getting Started
```
docker run --rm -p 5000:5000 ds-ml-service
```
เปิดเบราว์เซอร์และเข้าตรวจสอบที่ web browser

หน้าเว็บ: ```http://127.0.0.1:5000/```

ตรวจสอบสถานะ: ```http://127.0.0.1:5000/health```

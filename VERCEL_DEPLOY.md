# Deploy ke Vercel

Project ini memiliki `app.py` di root sebagai entrypoint Vercel.

Struktur root yang harus terlihat di repository Vercel:

```text
app.py
backend/
dist/
data/
data_live/
data_static/
model/
requirements.txt
.python-version
```

Di Vercel, arahkan Root Directory ke folder ini jika repository masih membungkusnya di dalam folder `Website Leptoscope`.

# Yılın Gününü Hesaplama

### Projenin Amacı Nedir?
Python'da fonksiyonlar kullanarak verilen bir tarihin yılın kaçıncı günü olduğunu hesaplamak.

### Program Ne İşe Yarar?
Girilen yıl, ay ve gün bilgilerine göre tarihin yıl içindeki sırasını belirler. Artık yılları dikkate alır ve geçersiz tarihler için `None` döndürür.

### Program Nasıl Çalışır?
1. `is_year_leap()` fonksiyonu yılın artık yıl olup olmadığını kontrol eder.
2. `days_in_month()` fonksiyonu ayların gün sayılarını belirler.
3. `day_of_year()` fonksiyonu belirtilen aydan önceki günleri toplar.
4. Girilen gün sayısını toplama ekler.
5. Geçersiz tarihlerde `None`, geçerli tarihlerde toplam gün sayısını döndürür.

### Kullanılan Python Yapıları Nelerdir?
- `def`, `return`
- `if`, `elif`, `else`
- `for` döngüsü
- `range()`
- Listeler
- `and`, `or`
- `None`, `True`, `False`
- `+=` operatörü

### Programın Beklenen Çıktısı Nedir?
```text
366
```

### Program Nasıl Çalıştırılır?
Python IDLE üzerinden `.py` dosyası açılır ve F5 tuşuna basılır.

### Kaynakça
Python Software Foundation. (t.y.). *The Python tutorial*. https://docs.python.org/3/tutorial/

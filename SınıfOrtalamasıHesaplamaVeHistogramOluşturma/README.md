# Sınıf Ortalaması Hesaplama ve Histogram Oluşturma

Bu proje, kullanıcıdan alınan notları harf notlarına çevirir ve bir histogram oluşturur.

## Özellikler

- Kullanıcıdan not sayısı ve notları alır
- Notları harf notlarına çevirir (A, B, C, D, F)
- Her not için tablo şeklinde çıktı verir
- Harf notlarının dağılımını gösteren histogram oluşturur

## Gereksinimler

- Python 3.x

## Nasıl Çalıştırılır

1. Terminali açın ve proje dizinine gidin:
   ```
   cd SınıfOrtalamasıHesaplamaVeHistogramOluşturma
   ```

2. Programı çalıştırın:
   ```
   python main.py
   ```

3. Program sizden not sayısını ve notları girmenizi isteyecektir.

## Örnek Kullanım

```
How many grades will you enter? 5
Enter grades:
85
92
78
65
88

No   Grades   Letter Grades
1     85       B
2     92       A
3     78       C
4     65       D
5     88       B

Histogram
---------
A = 1
B = 2
C = 1
D = 1
F = 0
```

## Not Aralığı

- A: 90-100
- B: 80-89
- C: 70-79
- D: 60-69
- F: 0-59
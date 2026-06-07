# NumPy — Dərs 1: Tapşırıqlar

> **Mövzu:** NumPy-yə Giriş — Array tipləri, ndarray, dtype, əsas funksiyalar

## Tapşırıq 1

Aşağıdakı Python listini NumPy array-ə çevir və print ilə göstər

```python
meyveler = [3, 7, 12, 5, 9, 1]
```

Sonra bu array-in aşağıdakı xüsusiyyətlərini istifadə elə

- Ölçüsü (shape)
- Ölçü sayı (ndim)
- Ümumi element sayı (size)
- Məlumat tipi (dtype)

## Tapşırıq 2

`np.zeros()` və `np.ones()` funksiyalarından istifadə edərək aşağıdakıları yarat:

1. 6 elementli, bütün dəyərləri **0** olan array
2. 4 elementli, bütün dəyərləri **1** olan array
3. Hər ikisini terminalda göstər və `dtype`-larını göstər

## Tapşırıq 3

`np.arange()` funksiyasından istifadə edərək aşağıdakı array-ləri yarat və terminalda göstər:

1. 1-dən 10-a qədər (10 daxil) tam ədədlər
2. 0-dan 20-yə qədər **yalnız cüt** ədədlər
3. 100-dən 0-a qədər **10-ar azalan** ədədlər

## Tapşırıq 4

`np.linspace()` funksiyasından istifadə edərək:

1. 0 ilə 1 arasında **6 bərabər aralıqlı** ədəd yarat
2. 0 ilə 100 arasında **11 bərabər aralıqlı** ədəd yarat
3. Hər iki array-in `shape` və `size`-ını göstər

 `np.linspace(başlanğıc, son, ədəd_sayı)`

## Tapşırıq 5

Bir mağazanın 5 günlük satış miqdarları aşağıdakı kimidir:

```
Bazar ertəsi:  150
Çərşənbə axşamı: 200
Çərşənbə:      175
Cümə axşamı:   220
Cümə:          300
```

Bu məlumatları NumPy array kimi yarat. Sonra:

- Array-i terminalda göstər
- `shape`, `ndim`, `size`, `dtype` dəyərlərinidə göstər

---

## Tapşırıq 6

Aşağıdakı üç Python listini ayrı-ayrı NumPy array-ə çevir. Hər birinin `dtype`-ını göstər

```python
tam_ededler  = [1, 2, 3, 4, 5]
onluq_ededler = [1.5, 2.7, 3.1, 4.9]
metn_ler     = ["alma", "armud", "gilas"]
```

## Tapşırıq 7

`np.arange()` ilə 1-dən 13-ə qədər (13 daxil) ədədlərdən ibarət array yarat və terminalda göstər. Aşağıdakı sualları kod ilə cavablar tapın

- Neçə element var?
- Neçə ölçülüdür?
- Ölçüsü (shape) nədir?

## Tapşırıq 8

Aşağıdakı tələbə hesab məlumatlarından NumPy array yarat:

```
Riyaziyyat: 85
Fizika:     72
Kimya:      90
Biologiya:  68
Tarix:      78
İnformatika: 95
```

Array-i yaratdıqdan sonra:

1. `shape`-ini çap et
2. `ndim`-ini çap et
3. `size`-ini çap et
4. `dtype`-ını çap et
5. `np.ones()` ilə eyni ölçüdə bir array yarat

## Tapşırıq 9 — Yekun Tapşırıq

Aşağıdakıları həll et:

1. `np.arange()` ilə 5-dən 50-yə qədər **5-ər artıb** gedən array yarat
2. `np.linspace()` ilə 0 ilə 1 arasında **10 ədəd** yarat
3. `np.zeros()` ilə **8 elementli** sıfır array yarat
4. `np.ones()` ilə **8 elementli** birlik array yarat
5. Yuxarıdakı hər array üçün `shape`, `ndim`, `size` və `dtype`-ı terminalda göstər

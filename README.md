# Odev1
### Insertion short

#### 1.adım

[22, 27, 16, 2, 18, 6]

#### 2.adım

[22, 27, 16, 2, 18, 6]

#### 3.adım

[16, 22, 27, 2, 18, 6]

#### 4.adım

[2, 16, 22, 27, 18, 6]

#### 5.adım

[2, 16, 18, 22, 27, 6]

#### 6.adım

[2, 6, 16, 18, 22, 27]

**Average case ortalarda olduğu için 18 dir**

### Selection short

#### 1.adım

[2, 3, 5, 8, 7, 9, 4, 15, 6]

#### 2.adım

[2, 3, 5, 8, 7, 9, 4, 15, 6]

#### 3.adım

[2, 3, 4, 8, 7, 9, 5, 15, 6]

#### 4.adım

[2, 3, 4, 5, 7, 9, 8, 15, 6]


# Odev2
### Merge Short

#### 1.adım

Sol taraf: [16, 21, 11]

Sağ taraf: [8, 12, 22]

#### 2.adım

**Sol tarafı böl**

[16, 21, 11] -> [16] ve [21, 11]
[21, 11] -> [21] ve [11]

#### 3.adım

**Sağ tarafı böl**

[8, 12, 22] -> [8] ve [12, 22]
[12, 22] -> [12] ve [22]

#### 4.adım

**Dizileri birleştir**

[21] ve [11] birleştirildiğinde: [11, 21] olur.

[16] ve [11, 21] birleştirildiğinde: [11, 16, 21] olur.

[12] ve [22] birleştirildiğinde: [12, 22] olur.

[8] ve [12, 22] birleştirildiğinde: [8, 12, 22] olur.

#### 5.adım

**En son iki tarafı birleştir**

[11, 16, 21] ve [8, 12, 22] birleştirildiğinde: [8, 11, 12, 16, 21, 22] olur.

**Big-o gösterimi: O(n log n)**


# Odev3
### Binary Search Tree

Dizi: [7, 5, 1, 8, 3, 6, 0, 9, 4, 2]

#### 1.adım

İlk eleman olan 7, root (kök) olur.

root 7'dir.

#### 2.adım

5, 7'den küçük olduğu için soluna eklenir.

root'un solunda 5 bulunur.

#### 3.adım

1, 5'ten küçük olduğu için 5'in soluna eklenir.

5'in solunda 1 bulunur.

#### 4.adım

8, 7'den büyük olduğu için sağına eklenir.

root'un sağında 8 bulunur.

#### 5.adım

3, 1'den büyük olduğu için 1'in sağına eklenir.

1'in sağında 3 bulunur.

#### 6.adım

6, 5'ten büyük olduğu için 5'in sağına eklenir.

5'in sağında 6 bulunur.

#### 7.adım

0, 1'den küçük olduğu için 1'in soluna eklenir.

1'in solunda 0 bulunur.

#### 8.adım

9, 8'den büyük olduğu için 8'in sağına eklenir.

8'in sağında 9 bulunur.

#### 9.adım

4, 3'ten büyük olduğu için 3'ün sağına eklenir.

3'ün sağında 4 bulunur.

#### 10.adım

2, 3'ten küçük olduğu için 3'ün soluna eklenir.

3'ün solunda 2 bulunur.

# Patika-Marge-Sort
[16,21,11,8,12,22] -> Merge Sort

1.adımda: [16,21,11],[8,12,22]
2.adımda: [16],[21,11], [8],[12,22]
3.adımda: [11,16,21], [8,12,22]
4.adımda: [8,11,12,16,21,22]
İkiye bölme (2^x = n)'den x=log(n) defa yapılır. Her bir adımın time complexity değeri O(n) olduğu için genel ifademiz; O(nlog(n))

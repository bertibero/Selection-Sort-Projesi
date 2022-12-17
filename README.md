# Selection-Sort-Projesi

ÖRNEK 1-) [22,27,16,2,18,6] -> Insertion Sort
Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
- Verinin 2.elemanı ilk elamanla kıyaslanır 22<27 olduğundan değişiklik yapılmaz.
- Verinin 3. elemanı 2. ve 1. elemanla kıyaslanır. 16<27 ve 16<22 olduğundan 16 ilk sıraya geçer. [16,22,27,2,18,6]
- Verinin 4. elemanı 3.,2., ve 1. elemanla kıyaslanır. 2<27, 2<22 ve 2<16 olduğundan 2 ilk sıraya geçer. [2,16,22,27,18,6]
- Bu şekilde bir sonraki elemanlar sırayla kıyaslanır. [2,16,18,22,27,6]
- [2,6,16,18,22,27]

- Big-O gösterimi: O(n^2)

- 18 sayısı > Average Case

ÖRNEK 2-) [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

- ADIM 1-) 7 Sayısı 3 ile kıyaslnır artık en küçük sayı 3'tür. Sonra 3 sırası ile 5,8,2 ile kıyaslanır. Artık yeni en küçük sayımız 2'dir. 2 sırasıyla 9,4,15, ve 6 ile kıyaslnır. En küçük hala kendisi olduğundan en başa yazılır. [2,3,5,8,7,9,4,15,6] 
- ADIM 2-) 2.sıradaki sayı olan 3 ile üstteki işlem tekrar edilir.[2,3,5,8,7,9,4,15,6]
- ADIM 3-) 3.sıradaki 5 ile işlem devam edilir. [2,3,4,8,7,9,5,15,6]
- ADIM 4-) [2,3,4,5,7,9,8,15,6]

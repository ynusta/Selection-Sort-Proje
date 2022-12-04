Selection-Sort-Proje
i<n
[22,27,16,2,18,6] => verilen dizinin sort türüne göre aşamalarını yazımı. 
(n=6) (i<n)
i=1 (Birinci eleman seçilerek referans kabul edilir) 
"i=1" ==> [22]
Birinci elemanın sagındaki dizinde  ilk elemanla  ">,<" kıyaslaması yapılarak konumlandırılacagı yer tespit edilir. 
Birinci elemandan büyükse sagına kücükse soluna yazılır.
  
22<27,   16,2,18,6            ( 16 için,dizinin solundaki iki sayı için de ayrı ayrı işlem tekrarlanır )
16<22<27,  2,18,6             ( 2 için ,dizinin solundaki üç sayı için de ayrı ayrı işlem tekrarlanır )
2<16<22<27,  18,6             ( 18 için ,dizinin solundaki dört sayı için de ayrı ayrı işlem tekrarlanır )
2<16<18<22<27,  6             ( 6 için ,dizinin solundaki beş sayı için de ayrı ayrı işlem tekrarlanır )
2<6<16<18<22<27    


  
  

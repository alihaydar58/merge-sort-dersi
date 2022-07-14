# merge sort dersi
[16,21,11,8,12,22] -> Sıralamayı Birleştir

1-Yukarıdaki sınıflandırma göre göre aşamalarını belgeleyin.
Cevap:
				[16,21,11,8,12,22]
				 / \
			     [16,21,11] [8,12,22]	
			       / \ / \
			[16,21] [11] [8,12] [22]
			  / \ | / \ |
			[16] [21] [11] [8] [12] [22]
 			   \ / \ / \ /
  			 [16,21] [8,11] [12,22]
                                \ / |
				[8,11,16,21] [12,22]
				         \ /
				   [8,11,12,16,21,22]
				

2-Big-O gösterimini yazınız.
Cevap: O(n*logn)



# Binory-Search-Tree

Binary Search Tree (İkili Ağaç Yapısı) node'lardan oluşur.

Node, bir veri yapısının en temel birimidir.

Algoritmada en üstte bulunan node'a root adı verilir.

Sırasıyla node'ları root ile kıyaslayarak yerleştirilir.

Node root değerinden küçükse soluna,büyükse sağına yerleştirilir.

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamaları:

7 root olarak seçilir. 5 değeri root değerinden küçük olduğu için sol tarafa yazılır.

![image](https://user-images.githubusercontent.com/117040674/198995748-e7e50add-99e1-4fb9-b550-2a3c3730bd5d.png)

1 değeri 7'den küçük olduğu için sola 5'ten de küçük olduğu için yine sola yazılır.

![197847051-5770c5aa-7e0c-4c06-9db7-b6257a47c991](https://user-images.githubusercontent.com/117040674/198995871-0f06b720-7dee-4d8c-ae28-427a225ca39a.png)

8 değeri 7'den büyük olduğu için sağ tarafa yerleştiririz.

![197847736-238498b5-2e23-4026-9732-9e071215b56d](https://user-images.githubusercontent.com/117040674/198995947-b6d45c19-944e-481c-9188-7f41824dba1e.png)

3 değeri 7'den küçüktür, 5'ten küçüktür ama 1'den büyüktür, bu yüzden 1'in sağ tarafına yazılır.

![197850771-452768de-2722-4fd7-b286-394f5723451c](https://user-images.githubusercontent.com/117040674/198996026-f3450cf5-7073-4135-ac3c-ccfd3a75166b.png)

6 değeri 7'den küçüktür, 5'ten büyüktür,5'in sağına yazılır.

![image](https://user-images.githubusercontent.com/117040674/198996106-cbddcb9b-b1c2-46ec-8f4b-394dc156d594.png)

0 değeri 7'den, 5'ten ve 1'den küçüktür, bu yüzden 0'ın soluna yazılır.

![image](https://user-images.githubusercontent.com/117040674/198996203-fa78e414-a32e-4ade-a344-3885fcc63d0d.png)

9 değeri 7'den ve 8'den büyüktür, 8'in sağına yazılır.

![image](https://user-images.githubusercontent.com/117040674/198996443-91b15109-889b-42f0-ab97-900d2e6147cd.png)

4 değeri 7'den ve 5'den küçüktür, 1'den ve 3'ten büyüktür, 3'ün sağına yazılır.

![image](https://user-images.githubusercontent.com/117040674/198996518-23979e8c-9142-4f91-a4ae-3a4423a53911.png)

2 değeri 7'den ve 5'den küçüktür, 1'den büyük ama 3'den küçüktür, 3'ün soluna yazılır.

Ve son olarak binary search tree görünümümüz böyledir:

![image](https://user-images.githubusercontent.com/117040674/198996591-878df69f-4ee4-4378-9257-6aaeac9889f2.png)

http://www.patika.dev/

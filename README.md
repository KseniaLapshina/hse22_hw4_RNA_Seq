# hse22_hw4

## Выравняли RNA-seq чтения на геном мыши.

Проверили качество RNA-seq чтения с помощью программы fastQC.
![image](https://user-images.githubusercontent.com/114621114/202844716-4796e16f-65f5-4a22-94b5-2363d0cfa1d7.png)
![image](https://user-images.githubusercontent.com/114621114/202844762-9a3a04fd-5806-49a6-bb7d-99b1ce188554.png)
![image](https://user-images.githubusercontent.com/114621114/202844775-35572231-f64d-498d-8089-079638754fe5.png)
![image](https://user-images.githubusercontent.com/114621114/202844809-13a44cb6-f8c3-4506-afc9-a368e4748c83.png)
![image](https://user-images.githubusercontent.com/114621114/202844842-bdf5de28-650c-4c1b-b946-b1c077d07427.png)
![image](https://user-images.githubusercontent.com/114621114/202844863-8ac9af41-56ae-4299-8ba9-519be5abc135.png)
![image](https://user-images.githubusercontent.com/114621114/202845055-5717b584-fc17-4a7e-a2ee-a35dcd5a401a.png)
![image](https://user-images.githubusercontent.com/114621114/202845080-675bf951-63a6-4c9b-875e-96dde27399ee.png)
![image](https://user-images.githubusercontent.com/114621114/202845094-522d4b8d-fd6b-4654-ba66-7b0b1c8ed441.png)
![image](https://user-images.githubusercontent.com/114621114/202845112-740ec1b6-bb1f-402c-89c0-10a54d3c86e6.png)
![image](https://user-images.githubusercontent.com/114621114/202845182-45c461f2-6761-4cdd-9066-3c5695ee9c9d.png)
![image](https://user-images.githubusercontent.com/114621114/202845205-82e6bf73-a2d3-4ff2-9889-54d9caa6f125.png)

Откартировали RNA-seq чтения на геном мыши с помощью программы HISAT2.

Отобрали уникально картированные чтения и посчитали их количество.

С помощью программы HTSeq подсчитываем количество чтений, попавших на каждый ген. Подсчитываем общее число чтений, соответствующих хотя бы одному гену.

Объединям все файлы .counts по генам в один общий файл ALL.counts.

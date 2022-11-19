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
![image](https://user-images.githubusercontent.com/114621114/202845281-5d88b5fa-9823-4f62-8238-d87af70d6c0f.png)
![image](https://user-images.githubusercontent.com/114621114/202845314-f6d7e9a2-b41e-4bc7-8205-32f104ab53d9.png)
![image](https://user-images.githubusercontent.com/114621114/202845332-15862c59-5f89-40ac-a14e-711b5068b718.png)
![image](https://user-images.githubusercontent.com/114621114/202845382-8525edbc-5b7b-4bfb-abe8-7e722534c53f.png)
![image](https://user-images.githubusercontent.com/114621114/202845400-3835ab31-bf7c-474e-b6aa-4a6e03ad5883.png)
![image](https://user-images.githubusercontent.com/114621114/202845416-bf29e14a-1ad5-47da-969d-b5131ad98a84.png)

Отобрали уникально картированные чтения и посчитали их количество.

С помощью программы HTSeq подсчитываем количество чтений, попавших на каждый ген. Подсчитываем общее число чтений, соответствующих хотя бы одному гену.

Объединям все файлы .counts по генам в один общий файл ALL.counts.

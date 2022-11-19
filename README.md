# hse22_hw4

## Выравняли RNA-seq чтения на геном мыши.
https://colab.research.google.com/drive/1qatthb6D-qLny6zjap_GZInmqvrexE1W?usp=sharing

### Проверили качество RNA-seq чтения с помощью программы fastQC.
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

### Откартировали RNA-seq чтения на геном мыши с помощью программы HISAT2.
![image](https://user-images.githubusercontent.com/114621114/202845281-5d88b5fa-9823-4f62-8238-d87af70d6c0f.png)
![image](https://user-images.githubusercontent.com/114621114/202845314-f6d7e9a2-b41e-4bc7-8205-32f104ab53d9.png)
![image](https://user-images.githubusercontent.com/114621114/202845332-15862c59-5f89-40ac-a14e-711b5068b718.png)
![image](https://user-images.githubusercontent.com/114621114/202845382-8525edbc-5b7b-4bfb-abe8-7e722534c53f.png)
![image](https://user-images.githubusercontent.com/114621114/202845400-3835ab31-bf7c-474e-b6aa-4a6e03ad5883.png)
![image](https://user-images.githubusercontent.com/114621114/202845416-bf29e14a-1ad5-47da-969d-b5131ad98a84.png)

### Отобрали уникально картированные чтения и посчитали их количество.
![image](https://user-images.githubusercontent.com/114621114/202845499-e1fe36a0-e305-42f8-bbfa-bdf12660bd1f.png)
![image](https://user-images.githubusercontent.com/114621114/202845522-df06dd51-4036-4596-b82c-1f65fe251eb7.png)
![image](https://user-images.githubusercontent.com/114621114/202845542-6d0573da-845b-46a7-89f7-f04ce2176d67.png)
![image](https://user-images.githubusercontent.com/114621114/202845558-1792df36-92eb-495e-995e-34e8a7472795.png)
![image](https://user-images.githubusercontent.com/114621114/202845571-ca2e2999-b35a-4b76-9fb8-5e621419bec7.png)
![image](https://user-images.githubusercontent.com/114621114/202845578-3ce2c9e0-a7fa-4b4f-98de-062e02f0dfa1.png)

### С помощью программы HTSeq подсчитываем количество чтений, попавших на каждый ген. Подсчитываем общее число чтений, соответствующих хотя бы одному гену.
![image](https://user-images.githubusercontent.com/114621114/202845665-373f4148-21b0-4145-bbe1-11539c1519f9.png)
![image](https://user-images.githubusercontent.com/114621114/202845690-89b76fbd-1170-4276-ab36-4c9762cc133a.png)
![image](https://user-images.githubusercontent.com/114621114/202845713-9a1e5a6b-7fd9-4d28-86e8-f7dd203fee2c.png)
![image](https://user-images.githubusercontent.com/114621114/202845738-4bc92fd5-6b9e-4006-88a9-9d78d08ab1c2.png)
![image](https://user-images.githubusercontent.com/114621114/202845759-c529f9d5-e6f9-4f5a-973b-d72310f87025.png)
![image](https://user-images.githubusercontent.com/114621114/202845770-2c0686bf-1e24-48aa-8dd4-179ce219b44a.png)

| ID образца | Тип образца | Общее кол-во исходных чтений | Кол-во и процент чтений, которые были успешно откартированы на геном | Кол-во и процент уникально откартированных чтений | Общее кол-во чтений, которые попали на гены |
| --- | --- | --- | --- | --- | --- |
| SRR3414629 | r1 | 21106089 | 20510113 (97.18%) | 18375888 (87.06%) | 16049609 |
| SRR3414630 | r2 | 15244711 | 14832680 (97.30%) | 13186139 (86.50%) | 11465324 |
| SRR3414631 | r3 | 24244069 | 23547686 (97.13%) | 20928945 (86.33%) | 18408851 |
| SRR3414635 | c1 | 20956475 | 20395865 (97.32%) | 18428317 (87.94%) | 16275997 |
| SRR3414636 | c2 | 20307147 | 19757059 (97.29%) | 17825380 (87.78%) | 15757580 |
| SRR3414637 | c3 | 20385570 | 19847291 (97.36%) | 17844858 (87.54%) | 15736978 |

### Объединям все файлы .counts по генам в один общий файл ALL.counts.

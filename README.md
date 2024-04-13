# final_task_on_specialization

1.	Используя команду cat в терминале операционной системы Linux, создать два файла Домашние животные (заполнив файл собаками, кошками, хомяками) и Вьючные животными заполнив файл Лошадьми, верблюдами и ослы), а затем объединить их. Просмотреть содержимое созданного файла. Переименовать файл, дав ему новое имя (Друзья человека)
2.	Создать директорию, переместить файл туда
 
 ![1, 2](https://github.com/VyrypaevNM/final_task_on_specialization/assets/135502758/ac7c5abd-8475-448d-92a4-e9a6c86f451a)

3.	Подключить дополнительный репозиторий MySQL. Установить любой пакет из этого репозитория.
 
 ![3](https://github.com/VyrypaevNM/final_task_on_specialization/assets/135502758/ebaeadf7-8e99-4abd-a2e1-562d319615d2)

4.	Установить и удалить deb-пакет с помощью dpkg.
 ![4](https://github.com/VyrypaevNM/final_task_on_specialization/assets/135502758/f5e08a51-5123-451a-ab1e-798d42943288)

5.	Выложить историю команд в терминале ubuntu
Task1
mkdir Final_test
echo ‘dog cat hamster’ > pets
cat pets
echo ’horse camel donkey’ > pack_animals
cat pets pack_animals > temp_file
cat temp_file
mv temp_file > human_friend
cat human_friend
Task2
mkdir task2
mv human_friend ./task2/
Task3
wget https://dev.mysql.com/get/mysql-apt-config_0.8.12-1_all.deb
sudo apt update
sudo apt install mysql-server
Task4
wget http://ftp.us.debian.org/debian/pool/main/p/python3-defaults/2to3_3.1![Uploading диаграмма.svg…]()
1.2-1_all.deb
sudo dpkg -i 2to3_3.11.2-1_all.deb
sudo dpkg -r 2to3_3.11.2-1_all.deb 


6.	Нарисовать диаграмму, в которой есть класс родительский класс, домашние животные и вьючные животные, в составы которых в случае домашних животных войдут классы: собаки, кошки, хомяки, а в класс вьючные животные войдут: Лошади, верблюды и ослы).
   
![диаграмма (1)](https://github.com/VyrypaevNM/final_task_on_specialization/assets/135502758/deb2dd57-48dd-4aa1-bce1-e52220bcda34)


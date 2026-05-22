Zadanie 1 : Uruchomienie lokalnej instalacji Apache Spark

<img width="859" height="319" alt="image" src="https://github.com/user-attachments/assets/6ab99f4c-5c46-4865-bf67-a4ccb21332db" />

<img width="851" height="363" alt="image" src="https://github.com/user-attachments/assets/f97f275a-4230-456b-afaf-8654ba74a57d" />

<img width="793" height="288" alt="image" src="https://github.com/user-attachments/assets/f59897dd-86e0-4f76-baa3-c3aada3e892e" />

Zainstalowałem i skonfigurowałem lokalnie narzędzie Apache Spark oraz sprawdziłem czy w konsoli poprawnie działa pyspark i spark-shell

Zadanie 2 : Podstawowe operacje na DataFrame w PySpark

<img width="856" height="168" alt="image" src="https://github.com/user-attachments/assets/593c27b2-a968-48e8-bd7c-4777322a9c88" />

<img width="531" height="264" alt="image" src="https://github.com/user-attachments/assets/0ceaa68c-e9e2-44a7-9d0b-132a4cb8aa80" />

Odpaliłem w terminalu Sparka i wczytałem do niego pobrane dane z Sales z Kaggle po czym wyświetliłem schemat za pomocą df.printSchema()

<img width="559" height="253" alt="image" src="https://github.com/user-attachments/assets/c0fd57ef-d55f-4f71-a0e6-1d519d83dc2e" />

Można użyć selekcji kolumn aby wyświetlić tylko te co mnie obchodzą

<img width="680" height="254" alt="image" src="https://github.com/user-attachments/assets/2e3c489c-e590-43c9-8d62-78f84717c916" />

Z DataFrame w Sparku można filtrować dane używając filter aby zobaczyć rekordy większe niż np. 4000 sprzedaży 

<img width="512" height="234" alt="image" src="https://github.com/user-attachments/assets/1b82c09f-d715-4d51-8508-0b12b1e1790f" />

Użyłem także grupowania i agregacji. Do niego dodałem przedrostek F z pyspark.sql.functions aby Spark zrozumiał intencję grupowania int i str

<img width="513" height="85" alt="image" src="https://github.com/user-attachments/assets/e5389df2-4fba-4f1e-a5ef-d8d51ded9555" />

Na sam koniec przekształciłem dane używając Pandas i zapisałem je do dane2.csv

Zadanie 3 : Praca z RDD w PySpark

<img width="816" height="162" alt="image" src="https://github.com/user-attachments/assets/978a1bca-301f-4073-a5fd-bae224bc0175" />

W tym zadaniu używając RDD wczytałem dane oraz samodzielnie parsowałem wiersze używając mapowania. Zliczyłem liczbę wierszy 

Wnioski : 

Spark DataFrame sprawnie przetwarza tabele i bazy danych, natomiast RDD służy do niskopoziomowych operacji na surowych plikach tekstowych i kolekcjach

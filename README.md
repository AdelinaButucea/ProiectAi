# ProiectAi

In acest proiect avem tentativa de a rezolva o problema intalnita agricultorilor si anume numararea fructelor inainte de coacere pentru estimarea 
recoltei.
Proiectul nostru functioneaza pe baza de input vizual si modelul de AI o sa numere fructele intalnite.
Am folosit modelul deepforest, antrenat pe imagini cu pomi cu mere, etichetate manual.
Pentru imagini de testare - https://drive.google.com/drive/folders/1SFyAyevMzMiZ_pokn4ZCM30j7hX9SBpZ?usp=sharing \n
Pentru pathul modelului - https://drive.google.com/file/d/1-Exl5JaBRmHBp3z_2Y4b2ybEOsLhraag/view?usp=sharing \n
Antrenarea modelului este prezentata in fisierul train.ipynb
Testarea se face in fisierul predict.ipynb
Proiectul a fost realizat in colab, unde recomandam testarea. Fisierul contine celule pentru instalarea tuturor dependintelor necesare.
Pathul modelului si al imaginii trebuie introduse manual.
Intr-o celula se afla functia 'predict' care va lua ca input pathul imaginii si argumentul 'd' care e numele modelului. 
Ea va returna imaginea cu dreptunghiuri in jurul merelor si numarul lor.

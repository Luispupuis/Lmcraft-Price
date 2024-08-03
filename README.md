# Lmcraft-Price
# How to create a new Block / Item / Tool / OPITEM / Enchat Price
Go into the Folder Block / Item or other catigory
Now Create a new File: Youre_Item_Name.LmCode
Content:
```yml
Lmcraft-reader-version: LATEST
ACTIVE: True
TYPE: Data/Others/Price
Main: src.Main

CODE:
  src:
    Main: -M DATAS
    DATAS:
      Material: Youre_Material
      Displayname: < Optinal >
      AdminShop-Price: 
         buy: < Optinal >
         sale: < Optinal >
       Price: Youre_Pice [ 10, 50, 35....: NOT FOR EXAMPLE 35.32 ]
```       
Information: This is a self-"programmed" language, the structure is similar to yml: The language is executed in Java and will soon be made available as an open source.

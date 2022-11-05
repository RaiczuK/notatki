# Programowanie Obiektowe - Kartkowka 1

## CMD

```md
# dir - Printuje wszystkie foldery i pliki 
# tree - Printuje wszystkie podfoldery (nie pliki)
# tree /f - Printuje wszystkie podfoldery i pliki
# cd - Printuje sciezke do folder w ktorym jestesmy
# cd [folder] - Przenosi cie do innego folderu (.. to rodzic)
# dotnet new console - Tworzy nowy console project
```

n.p Jezeli nasza struktura folderow wyglada tak:

```
- C:/
    - Users/
        - Tomasz/
            - Documents/
                - Programowanie/
                    - C#/
                        - Projekt/
                            - Classes/
                                - Class1.cs
                            - Program.cs
                            - plik1.cs
                        - plik1.cs 
                        - plik2.cs
                        - plik3.cs
```

i w terminalu znajdujemy sie w folderze

```
C:\Users\Tomasz\Documents\Programowanie\C#
```
to
```md
# dir - zwroci nam:

<DIR>   Projekt
        plik1.cs
        plik2.cs
        plik3.cs

<DIR> mowi nam, ze dany element jest folderem

# tree - zwroci nam:

C:.
|---> Projekt
|       |---> Classes

# tree /f - zwroci nam:

C:.
|---> Projekt
|       |---> Classes
|       |       |---> Class1.cs
|       |---> Program.cs
|       |---> plik1.cs
|---> plik1.cs
|---> plik2.cs
|---> plik3.cs

# cd - zwroci nam:

C:\Users\Tomasz\Documents\Programowanie\C#

# cd Projekt - Zmieni nasza sciezke na:

C:\Users\Tomasz\Documents\Programowanie\C#\Projekt

```

## C#

```C#
Console.WriteLine("Hello World!"); // Printuje "Hello World"
```

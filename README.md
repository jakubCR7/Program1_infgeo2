## Informatyka Geodezyjna II
## Projekt 1 - Transformacje 
Program umożliwia implementację transformacji geodezyjnych zgodnie z potrzebami użytkownika.

## Wymagania do obsługi programu:
Program został stworzony z użyciem programu Python 3.11.5, zaimporotwana została biblioteka NumPy, pozwalająca na wykonywanie obliczeń numerycznych i naukowych. Program został napisany w dla systemu operacyjnego Microsoft Windows 10 PRO i wyższych.

## Funkcje programu:
**Użytkownik wybiera spośród dostępnych elipsoid:**
'''
GRS80
WGRS84
Krasowski
'''
**Użytkownik wybiera spośród dostępnych transformacji:**
'''
 1 = X, Y, Z --> phi, lam, h 
 2 = phi, lam, h --> X, Y, Z 
 3 = X, Y, Z --> neu 
 4 = BL --> X2000, Y2000 
 5 = BL --> X92, Y92
'''
### Działanie programu:
Uruchamiając program Python wymagane jest również podanie nazwy pliku ze współrzędnymi wraz z jego rozszerzeniem (((tutaj trzeba o nagłówku i zerach wpisać))). Następnie, zgodnie z instrukcjami programu należy wybrać elipsoidę. Następnie, poprzez wpisanie liczby od 1 do 5, dokonujemy wyboru transformacji. Opcje, spośród których dokonujemy wyboru są podane powyżej w punkcje **Funkcje programu**.

### Przykładowe użycie programu:
1. Użytkownik uruchamia konsolę CMD (wiersz poleceń) w folderze, w którym znajduje się program.<br>
***cd C:\Users\admin\Desktop\Program1***
2. Program uruchamia się poprzez wpisanie poleceń ***python**, po spacji nazwa programu ***Program1.txt***, oraz po spacji nazwa pliku z danymi np. ***wsp_int.txt***
3. Wymagania wobec pliku z danymi:
   - nagłówek może być dowolny
   - separatorem danych jest przecinek ','
   - dane muszą być różne od 0, inaczej program nie będzie działał
   - przykładowy wygląd pliku: <br>
   ----- X ----- Y ----- Z ----- <br>
   1009.9999,1008.8889,107.777
 4. Wybór elipsoidy np. ***GRS80***
 5. Wybór transformacji poprzez wskazanie odpowiedniej cyfry, np. X,Y,Z-->neu ***1***

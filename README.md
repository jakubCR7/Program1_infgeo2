## Informatyka Geodezyjna II
## Projekt 1 - Transformacje 
Program umożliwia implementację transformacji geodezyjnych zgodnie z potrzebami użytkownika.

## Wymagania do obsługi programu:
Program został stworzony z użyciem programu Python 3.11.5, zaimporotwana została biblioteka NumPy, pozwalająca na wykonywanie obliczeń numerycznych i naukowych. Program został napisany w dla systemu operacyjnego Microsoft Windows 10 PRO i wyższych.

## Funkcje programu:
**Użytkownik wybiera spośród dostępnych elipsoid:** <br>
GRS80<br>
WGRS84<br>
Krasowski <br>

**Użytkownik wybiera spośród dostępnych transformacji:** <br>
 1 = X, Y, Z --> phi, lam, h <br>
 2 = phi, lam, h --> X, Y, Z <br>
 3 = X, Y, Z --> neu <br>
 4 = BL --> X2000, Y2000 <br>
 5 = BL --> X92, Y92<br>
### Działanie programu:
Uruchamiając program Python wymagane jest również podanie nazwy pliku ze współrzędnymi wraz z jego rozszerzeniem (((tutaj trzeba o nagłówku i zerach wpisać))). Następnie, zgodnie z instrukcjami programu należy wybrać elipsoidę. Następnie, poprzez wpisanie liczby od 1 do 5, dokonujemy wyboru transformacji. Opcje, spośród których dokonujemy wyboru są podane powyżej w punkcje **Funkcje programu**.

### Przykładowe użycie programu:
1. Użytkownik uruchamia konsolę CMD (wiersz poleceń) w folderze, w którym znajduje się program.<br>
**cd C:\Users\admin\Desktop\Program1**
2. Program uruchamia się poprzez wpisanie poleceń **python**, po spacji nazwa programu **Program1.txt**, oraz po spacji nazwa pliku z danymi np. **wsp_int.txt**
3. Wymagania wobec pliku z danymi:
   - nagłówek może być dowolny
   - separatorem danych jest przecinek ','
   - dane muszą być różne od 0, inaczej program nie będzie działał
   - przykładowy wygląd pliku: <br>
   ----- X ----- Y ----- Z ----- <br>
   1009.9999,1008.8889,107.777
 4. Wybór elipsoidy np. **GRS80**
 5. Wybór transformacji poprzez wskazanie odpowiedniej cyfry, np. X,Y,Z-->neu **1**

Przy zastosowaniu prawidłowej ścieżki i odpowiednich poleceń program powinien się uruchomić, następnie wyświetlić komunikat:<br>
**program zapisał plik o nazwie "nazwapliku.txt" ze współrzędnymi geodezyjnymi w bierzącym folderze**
#### Przykładowe użycie pliku:
Aby program zadziałał, dane w pliku muszą spełniać wyżej przedstawione wymogi, można zweryfikować za pomocą przykładowych plików umieszczonych na stronie.<br>
Dane wejściowe:'wsp_inp.txt'<br>
Pod nagłówkiem dane zapisane są w trzech kolumnach, pierwsza to współrzędne X, druga to współrzędne Y, a trzecia to wysokość Z, wszystkie wartości podane w metrach.<br>

Dane wyjściowe:<br>
W pliku wyjściowym dane są rozłożone tak, jak w pliku wejściowym.

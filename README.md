# docs
Dokumentacja projektu, cel powstania

## Cele
projekt aplikacji
opracowanie standardu modeli szacowania


## Korzyści
wsparcie społeczności wokół budowania mechanizmów 
Własne i importowane modelowanie


## Format standardu
estimation.yaml

w nim są opsiane scenariusze i deklarowane wartości wejściowe oraz wyjściowe i zależności

## Jak to ma działać?

w praktyce musi być możliwość symulacji biorącej pod uwagę następujące czynniki wyjściowe:
+ czas:
  + stworzenia specyfikacji
  + tworzenia dokumentacji przed i po wdrożeniowej
  + realizacji testów:
    + manualne: 
      + funkcjonalność: x3
      + zależność x3
    + automatyczne x1
    + pół-automatyczne x2
      
+ jakość:
  + czytelność napisanego kodu (nakłady na refaktoring po sporządzeniu dokumentacji + 100% pisania kodu)



chodzi o nie tworzenie specyficznych czasów, a stworzenie mapy zależności
aby możliwe było obliczenie w zależności od ilości pracowników i ich znajomości technologii i znajomości 
czasu jaki jest potrzebny na wytworzeni oprogramowania



Istotne są też warunki zewnętrzne jak:
warunki zatrudnienia, oczekiwania zleceniodawca,

które mogą wpłynąć na ryzyko przedłużenia czasu realizacji.

## Inne zagadnienia

Przeliczanie na podastawie zmiennych


Specyfikacja zmawiającego
	Czy jest dokladna, przez koogo pisana
	
	
Kto będzie wykonywał


Jakie wersje programowania maja być dostepne

	Na jaka platforme
	Czy w czystym jezykyu programowania,
	Czy w okreslonym srodowisku
	
	
Spospoby sprawdzenia poprawnosci

	Czy mozliwosc w jednej linicje
	Czy trzeba wyklikac


Rozpisać warstwy aplikacji i duplikowane rónoległe warstwy do których trzeba zrobić pobrycie
Np.
modele danych + mysql

Czas wykonania zamiast x2 w przypadku równoległych jest do potęgi, czyli x4
Bo mogą wystąpić pośrednie błędy

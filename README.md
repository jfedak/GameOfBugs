## Czym jest GameOfBugs?

GameOfBugs to cyfrowa wersja gry "Hive", która jest strategiczną grą turową przeznaczoną dla dwóch osób. W skład GameOfBugs wchodzi 22 sześciokątnych płytek - 11 czarnych i 11 białych. Na płytkach znajdują się mniej lub bardziej lubiane komunikaty z systemu Satori, przy czym każdy z nich porusza się w unikalny sposób. Celem gry jest całkowite otoczenie królowej przeciwnika dowolnymi płytkami (niekoniecznie płytkami swojego koloru). Gracz, który uczyni to jako pierwszy zostaje zwycięzcą.

### Układanie płytek

Rozgrywka rozpoczyna się od wyłożenia przez każdego z graczy jednej płytki. Każda kolejna dokładana płytka musi zostać umieszczona tak, aby po wprowadzeniu do gry sąsiadowała jedynie z płytkami swojego koloru. Wyłożona płytka może być w następnych turach (o ile gracz wyłożył już królową) przekładana na pozycję, w których będzie sąsiadowała z płytkami innego koloru. Raz położonej płytki nie można usunąć aż do końca gry.

### Wyłożenie królowej

Królowa musi być zagrana w ciągu pierwszych czterech tur danego gracza. Jeżeli na początku czwartej tury gracz nie ma wyłożonej królowej, to musi wprowadzić ją do gry.

### Poruszanie płytkami

Za wyjątkiem królowej gracz nie musi wprowadzić do gry wszystkich posiadanych płytek, aby mieć możliwość poruszania tymi, które już znajdują się w grze. W swojej turze gracz wybiera, czy chce dołożyć kolejną płytkę do gry, czy też chce przesunąć jedną płytkę już znajdującą się w grze (poruszanie płytkami jest dostępne dopiero po wyłożeniu własnej królowej).

### Zasada spójności

Wyłożone płytki muszą przez cały czas być ze sobą połączone. W żadnym momencie nie może nastąpić sytuacja, w której zbiór wszystkich płytek w grze będzie niespójny. Zasada ta może działać zarówno na korzyść jak i na niekorzyść gracza - z jednej strony nie będziemy w stanie przemieścić każdej z płytek, jednak z drugiej strony odpowiednie układanie własnych płytek może ograniczyć przeciwnikowi swobodę ruchu.

### Swoboda ruchu

Wszystkie płytki mogą poruszać się tylko wtedy, gdy nie są zablokowane. Jeśli wysunięcie płytki spowodowałoby przesunięcie innych elementów, to nie możemy nią poruszać. Podobnie płytka nie może znaleźć się na pozycji, na którą nie można jej wsunąć bez naruszania struktury roju.

### Rodzaje płytek oraz ich ruchy

**Królowa** _(komunikat - **OK**)_

Najważniejszy element gry, ponieważ przez cały czas musimy uważać na jej sąsiadów. Królowa jednak nie może wykonywać spektakularnych ruchów - w danej turze gracz może przemieścić tę płytkę jedynie na pole będące jej sąsiadem. Mimo niewielkich możliwości, pojedynczy ruch królową jest w stanie zmniejszyć jej liczbę sąsiadów, a zatem może znacząco pokrzyżować plany przeciwnika.

**Mrówka** _(komunikat - **ANS**)_

Mrówka może poruszać się na dowolne miejsce wokół roju, do którego może dojść bez naruszania jego struktury _(patrz "Swoboda ruchu")_. Dzięki tak dużej mobilności jest to jedna z najbardziej wartościowych płytek w grze.

**Konik polny** _(komunikat - **RTE**)_

Konik polny nie porusza się w zwykły sposób, ale skacze ze swojej pozycji na pierwszą wolną pozycję, poruszając się wzdłuż płytek położonych w linii prostej. Dzięki temu może zapełniać miejsca otoczone przez inne płytki, ponieważ jego ruch nie narusza struktury roju. Należy jednak pamiętać o tym, że podczas ruchu konik polny musi przeskoczyć przynajmniej jedną płytkę.

**Pająk** _(komunikat - **TLE**)_

Pająk podczas jednej tury porusza się wokół roju o dokładnie trzy pola, dodatkowo nie może w tym samym ruchu wracać po swoich śladach. Pająk może się poruszać tylko naokoło płytek z którymi może się bezpośrednio zetknąć w każdej fazie swojego ruchu.

**Żuk** _(komunikat - **MEM**)_

Żuk, podobnie jak królowa, może poruszać się tylko o jedno pole podczas tury. Jednak w przeciwieństwie do pozostałych owadów może wspinać się na rój. Owad, na którym znajduje się żuk, jest unieruchomiony. Podczas dokładania nowych płytek przyjmuje się, że stos jest w kolorze żuka znajdującego się na jego szczycie. Żuk posiada umiejętność wchodzenia w miejsca otoczone ze wszystkich stron, jednak w dalszym ciągu obowiązuje go reguła swobody ruchu. Żuka znajdującego się na górze roju można zablokować stawiając na nim innego żuka, w szczególności wszystkie cztery żuki mogą być ustawione jeden na drugim. Do gry jest on wprowadzany tak samo jak pozostałe owady.

**Biedronka** _(komunikat - **CME**)_

Biedronka jest dodawana do gry tak samo jak pozostałe płytki. Podczas ruchu biedronka porusza się o trzy pola - dwa na górze roju oraz jedno w dół (ostatni etap ruchu to zejście z roju). Dzięki temu może wchodzić w miejsca otoczone ze wszystkich stron.

**Komar** _(komunikat - **QUE**)_

Komar jako jedyny owad nie posiada własnego sposobu poruszania. Zamiast tego za każdym razem przejmuje zdolność ruchu jednego ze swoich sąsiadów (jednak gdy jest na górze roju, porusza się jak żuk). Należy pamiętać, że komar sam w sobie nie posiada żadnego sposobu poruszania, zatem gdy jego jedynym sąsiadem jest inny komar, to nie może wykonać ruchu. 
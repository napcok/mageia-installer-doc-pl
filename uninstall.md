# Odinstalowywanie Magei

Jeśli Mageia cię potrafiła Cię do siebie przekonać lub nie byłeś w stanie jej poprawnie zainstalować po prostu musisz się jej pozbyć. To jest Twoje prawo i Mageia daje Ci taką możliwość. Co nie jest takie oczywiste w przypadku innych systemów operacyjnych.

Uruchom system za pomocą instalacyjnej płyty DVD z Mageią, wybierz **System ratunkowy**, a następnie **Przywróć program rozruchowy Windows**. Po następnym uruchomieniu będziesz mieć dostęp wyłącznie do Windows, bez opcji wyboru systemu opracyjnego.

Aby odzyskać miejsce na dysku użytę przez Mageią należy pod Windowsem: kliknąć ```
Start -> Control Panel -> Administrative Tools -> Computer Management -> Storage -> Disk Management```
 aby dostać się do narzędzia zarządzającego partycjami. Rozpoznasz partycję Magei ponieważ będą one oznaczone jako **Nieznane (Unknown)**. Kliknij prawym przyciskiem myszy na te partycje i wybierz **Usuń (Delete)**. Miejsce zostanie oznaczone jako wolne.

Jeśli używasz **Windows XP**, możesz utworzyć nowe partycje i sformatować je jako **FAT32** lub **NTFS**. Zostanie im przydzielona "litera dysku".

Jeśli używasz **Vista** lub **7**, masz dodatkowo jedną możliwość, możesz rozszerzyć istniejącą partycję, która znajduje się po lewej stronie od wolnego miejsca. Dostępne są również inne narzędzia do partycjonowania, takie jak **gparted**, działające zarówno pod Windows jak i Linux. Jak zawsze, przy operacji zmieniania partycji, bądź bardzo ostrożny i upewnij się że masz kopię wszystkich ważnych danych.

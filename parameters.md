# Różne parametry systemowe

![](./images/dx2-summary.png)

Instalator DrakX, opierając się na twoich poprzednich wyborach oraz na detekcji sprzętu, proponuje zazwyczaj bardzo rozsądne ustawienia konfiguracji różnych aspektów działania systemu. Na tym ekranie możesz dokonać ich przeglądu oraz pozmieniać niektóre z nich jeśli chcesz - kliknij **Konfiguruj**.

##System

* **Strefa czasowa**

    Instalator ustawia strefę czasową, na podstawie wybranego języka. Możesz ją oczywiście dowolnie zmieniać. Zobacz [Konfiguruj strefę czasową](./timezone.md).

* **Kraj / Region**

    Jeśli nie znajdujesz się w zaznaczonym kraju, jest bardzo ważne by poprawić to ustawienie. Zobacz [Kraj / Region](./country.md).

* **Program rozruchowy**

    DrakX dokonał odpowiednich ustawień programu rozruchowego.

    Nie zmieniaj ich, jeśli nie wiesz jak skonfigurować Grub.

    Aby uzyskać więcej informacji, zobacz [Podstawowe opcje programu rozruchowego](./bootloader.md).

* **Zarządzanie użytkownikami**

    Tutaj możesz utworzyć dodatkowych użytkowników. Dla każdego z nich zostanie utworzony katalog domowy - **/home/nazwa_użytkownika**.

* **Usługi**

    Usługi systemowe odnoszą się do tych niewielkich programów, które działają w tle (daemony). Tutaj możesz aktywować lub zdeaktywować ich uruchamianie przy starcie systemu.

    You should check carefully before changing anything here - a mistake may prevent your computer from operating correctly.

    Aby uzyskać więcej informacji, zobacz [Konfiguracja usług](./services.md).

##Parametry sprzętu

 * **Klawiatura**

    This is where you setup or change your keyboard layout which will depend on your location, language or type of keyboard.

 * **Mysz**

    Here you can add or configure other pointing devices, tablets, trackballs etc.

 *  **Karta dźwiękowa**

    The installer uses the default driver, if there is a default one. The option to select a different driver is only given when there is more than one driver for your card, but none of them is the default one.

*  **Interfejs graficzny**

    This section allows you to configure your graphic card(s) and displays.

    Aby uzyskać więcej informacji, zobacz [Konfiguracja monitora i karty graficznej](monitor.md).

![](./images/dx2-summaryBottom.png)

##Sieć i Internet

* **Sieć**

    You can configure your network here, but for network cards with non-free drivers it is better to do that after reboot, in the Mageia Control Center, if you have not yet enabled the Nonfree media repositories.

---

***Ostrzeżenie***

Jeśli dodasz kartę sieciową, nie zapomnij ustawić tak zaporę sieciową, aby dziłała również na nowym interfejsie.

---

* **Serwery pośredniczące**

    A Proxy Server acts as an intermediary between your computer and the wider internet. This section allows you to configure your computer to utilize a proxy service.

    You may need to consult your systems administrator to get the parameters you need to enter here

##Bezpieczeństwo

* **Poziom bezpieczeństwa**

    Here you set the Security level for your computer, in most cases the default setting (Standard) is adequate for general use.

    Check the option which best suits your usage.

* **Zapora sieciowa**

    A firewall is intended to be a barrier between your important data and the rascals out there on the internet who would compromise or steal it.

    Select the services that you wish to have access to your system. Your selections will depend on what you use your computer for.

---

***Ostrzeżenie***

    Bear in mind that allowing everything (no firewall) may be very risky.


---

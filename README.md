Dokumentation meiner privaten VoIP-Telefonanlage.

Ich betreibe als VoIP-Server eine ausgediente FritzBox 7240 an einem Telekom AllIP DSL-Anschluss.
Als Telefone kommen folgende Geräte zum Einsatz:
- Siemens S685IP DECT Basisstation, der SIP an die FritzBox angebunden
- Cisco 7960 Systemtelefon, per SIP an die FritzBox angebunden
- 4x Cisco 7961 Systemtelefon, per SIP an die Fritzbox angebunden

Meine Dokumentation soll mir als Gedächtnisstütze dienen und anderen Leute helfen, 
die ein ähnliches Setup fahren möchten. Die Doku habe ich als PDF und TeX in diesem
Repo zur Verfügung gestellt.

Link zum PDF:
https://github.com/mkirbst/cisco7960fritzbox/blob/master/anleitung-voip-fritzbox-cisco.pdf

Beispielhafte Konfigurationsdateien für ein Cisco 7960, die zusätzlich zur SIP-Firmware von
Cisco gebraucht werden finden sich in diesem Ordner (sind auch im PDF aufgeführt):
https://github.com/mkirbst/cisco7960fritzbox/configs_cisco7960


WARNUNG: Ich bin nicht verantwortlich wenn ihr bei dem Versuch das nachzustellen eure Hardware in Briefbeschwerer verwandelt. Ich
beschreibe hier nur nach bestem Wissen und Gewissen, wie es bei mir geklappt hat. Wie immer gilt: 


 -- Gehirn einschalten, nachmachen auf eigene Gefahr !! --


HINWEIS ZU FIRMWARE-/BIOS UPDATES IM ALLGEMEINEN: Bei einem Firmware-/BIOS-Update die Geduld zu verlieren und den Stecker zu ziehen,
weil sich mal 10 Minuten nichts regt, ist der sicherste Weg eure Hardware kaputt zu machen ! Im Zweifel über Nacht stehen lassen, wenn
sich bis zum nächsten Morgen immernoch nichts getan hat, kann man immernoch neustarten. Beispielsweise laufen die Cisco 7961 mit Java und
brauchen locker mal eine halbe Stunde, wenn man die SIP-Firmware updatet. 

# Tipps für die Dokumentation und Bereitstellung von Code auf GitHub:

## Die Readme-Datei

Die Readme-Datei ist der Teil des Repositoriums, der einen Überblick über alle wesentlichen Informationen zum Code und zum Enstehungskontext des Codes bietet.

Sie ist Teil der technischen Dokumentation, die darauf abzielt: 

•	Die digitale Anwendung (einschließlich ihrer Schnittstellen) muss in geeigneter Weise verständlich und nachvollziehbar in Deutsch oder Englisch dokumentiert sein. 
•	Die Dokumentation soll anderen Museen und ihre Dienstleister in die Lage versetzen, die Struktur des Systems, den Ablauf der Datenverarbeitung, die Funktionen der einzelnen Einheiten und die Bedeutung von verwendeten Daten zu verstehen. Es wird empfohlen die Verständlichkeit der Dokumentation mit Screenshots (ggf. Erklärvideos) zu erleichtern.  

Der Text der Readme-Datei sollte mindestens folgende Abschnitte in folgender Reihenfolge enthalten:

<b>1.	Name der Anwendung</b>
Bezeichnung entspricht dem Titel der Anwendung  und auf der Website. Bitte achten Sie auf eine einheitliche Terminologie.

<b>2.	Kurzbeschreibung</b>
Beschreiben Sie in mind. drei Sätzen, um was es in der hinterlegten Anwendung geht.
z.B.: „‘Tromp L’Oeil‘ ist eine prototypische mobile Augmented-Reality-App für die Sammlungsstücke der Gemäldegalerie der Staatlichen Museen zu Berlin. Mit dieser Augmented-Reality-Anwendung werden Potentiale untersucht, die AR-Technologie zur Erforschung, Darstellung, Erzählung und Vermittlung von kulturellen Inhalten bietet. […]“


<b>3.	Inhaltsverzeichnis (Optional) </b>
Ermöglichen Sie den Leser*innen einen Schnelleinstieg in die folgenden Kapitel des Readme, indem Sie ein Inhaltsverzeichnis mit Sprungmarken zu den einzelnen Abschnitten erstellen.

<b>4. Entstehungskontext & Förderhinweis </b>
Textbaustein:
Diese [Art der Webanwendung angeben, z.B. Website, Progressive-Web-App] ist entstanden im Verbundprojekt museum4punkt0 – Digitale Strategien für das Museum der Zukunft, Teilprojekt [Teilprojektname einfügen gemäß Verbund-Website, Kurzform möglich]. Das Projekt museum4punkt0 wird gefördert durch die Beauftragte der Bundesregierung für Kultur und Medien aufgrund eines Beschlusses des Deutschen Bundestages. Weitere Informationen:
www.museum4punkt0.de
Falls benötigt – Englische Variante:
This [digital application] is part of the project museum4punkt0 - Digital Strategies for the Museum of the Future, sub-project [englischer Teilprojektname einfügen, gemäß museum4punkt0-Website]. The project museum4punkt0 is funded by the Federal Government Commissioner for Culture and the
Media in accordance with a resolution issued by the German Bundestag (Parliament of the Federal Republic of Germany). Further information: www.museum4punkt0.de
Zusätzlich muss im Rahmen der Projektförderung aus dem Rettungs- und Sofortprogramm
„Neustart Kultur“ das entsprechende Logo eingebunden werden. Daher bietet sich an, gleich beide Logos von BKM am Ende des Förderhinweises zu platzieren.

Die beiden Logos sind auf GitHub verfügbar unter:
https://github.com/museum4punkt0/images/blob/2c46af6cb625a2560f39b01ecb8c4c360733811c/ BKM_Fz_2017_Web_de.gif
https://github.com/museum4punkt0/media_storage/blob/a35eedb36e5b502e90cd76d669a6b3370 02b230a/BKM_Neustart_Kultur_Wortmarke_pos_RGB_RZ_web.jpg
Dort finden Sie auch einen Code-Snippet, mit dem die beiden Logos aus der Readme heraus verlinkt werden können.



<b>5.	Installation</b>
Geben Sie Benutzer*innen Informationen zur Installation / zum Aufsetzen der Anwendung und dazu benötigte Hard-/Software.

<b>6.	Benutzung</b>
Beschreibt die Benutzung der Anwendung nach der Installation. Fügen Sie bestenfalls Screenshots ein, um die Handhabung zu illustrieren. Auch Anforderungen an Geräte / Ausstattung bzw. Systemvoraussetzungen für den Betrieb sollten hier genannt sein. Falls Ihre Anwendung über ein Backend verfügt, sollte Ihnen ein Benutzerhandbuch für die Backend-Nutzung vorliegen. Stellen Sie dieses bitte auch zur Verfügung indem Sie es (als PDF/A-3) im Github Repository hochladen und in der Readme-Datei darauf verlinken. Existiert zudem ein Betriebskonzept, sollten Sie dieses von hier aus per Link zugänglich machen.

<b>6.	Beteiligung (optional)</b>
(Optional) Geben Sie hier an, ob und in welcher Art man sich an Ihrer Programmierung beteiligen kann. Detailinformationen werden in einer separaten Datei angelegt. Weitere Hinweise hierzu finden Sie unter https://help.github.com/en/articles/setting-guidelines-for-repository-contributors 

<b>7.	Credits</b>
Auftraggeber*in/Rechteinhaber*in (Name Ihrer Institution)
Urheber*innen (Namen der beteiligten Entwickler*innen oder Firma)
Die Autor*iInnen des Codes bzw. zugehörige Agenturen/Firmen/Institutionen können hier verlinkt sein. 


<b>8.	Lizenz / License</b>
Rechteangabe nach dem Schema: Copyright © Jahr, Institution / Urheber*innen.
Geben Sie hier an, unter welcher Lizenz der Quellcode/die Anwendung steht. Fügen Sie dem Repository die entsprechende Lizenz als Datei hinzu (GitHub stellt entsprechedne Vorlagen zu Verfügung) und verlinken zu dem zutreffenden Lizenztext. Bitte fügen Sie ferner eine Liste der Lizenzen für wiederverwendete Programmteile Dritter der Dokumentation hinzu.

Bitte formatieren Sie die einzelnen Abschnitte Ihres Readme als Überschriften. Im Readme-Editor setzen Sie dazu vor Abschnittsbegriffe ein #(+Leerzeichen). Dies erhöht die Lesbarkeit und vereinfacht die Auffindbarkeit z.B. von Lizenzinformationen. Weitere Hilfestellungen zur Anfertigung einer Readme-Datei und zur Codedokumentation finden Sie hier: 
https://guides.github.com/features/wikis/#creating-a-readme
https://docs.github.com/en/github/building-a-strong-community/adding-a-license-to-a-repository
https://technical-reference.readthedocs.io/en/latest/developer-guidelines/02-readme.html
https://technical-reference.readthedocs.io/en/latest/developer-guidelines/03-documentation.html




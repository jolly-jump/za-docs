===========================
 Nutzung des E-Mail-Kontos
===========================

Seit dem 1.Mai 2019 funktioniert der E-Mail-Zugang nur noch über
externe Protokolle, das bedeutet, dass Sie ein E-Mail-Programm
(E-Mail-Client) auf einem eigenen Gerät installieren müssen. Diese
Programm verbindet sich dann mit dem Lehrer-Server und lädt E-Mails
herunter.

Momentan funktioniert nur das Empfangen von E-Mails über IMAP/993 mit
Hilfe der Zugangsdaten <zaXXX> / <passwort>.

Im Weiteren wird dokumentiert, wie Sie mit Hilfe des Programms
Thunderbird an Ihre E-Mail-Konto kommen. Das gleiche sollte auch mit
jedem anderen modernen (auch mobilen) Mail-Client funktionieren. Bei
Thunderbird ist angenehm, dass er die richtigen Einstellungen
automatisch findet.


Thunderbird installieren
========================

- Laden Sie den neuesten Thunderbird für Ihr Betriebssystem herunter:
  https://www.thunderbird.net/de/ . Linuxbenutzer sollten
  selbstverständlich den thunderbird Ihrer Distribution installieren
  und verwenden.
- Installieren Sie Thunderbird und starten Sie das Programm zum ersten
  Mal.

Falls beim ersten Starten das Dialogfenster "Willkommen" erscheint,
wählen Sie "Überspringen und meine existierende E-Mail-Adresse
verwenden".

.. figure:: media/thunderbird-firststart.png

Ansonsten wählen Sie im Menü unter *Datei* -> *Neu* bzw. unter *Neue
Nachricht* unter dem Untermenü -> *Existierendes E-Mail-Konto...*

.. figure:: media/thunderbird-newaccount.png	    


Mailkonto einrichten
====================

Anschließend wird ein neues Konto eingerichtet, dabei geben Sie Name,
E-Mail-Adresse und Passwort ein. Ersetzen Sie dabei ``za3966`` durch
Ihr eigenes Benutzerkonto. Wenn Sie das Passwort speichern, sollten
Sie als Sicherheitsmaßnahme wenigstens `in Thunderbird ein
Master-Passwort vergeben
<https://support.mozilla.org/de/kb/master-passwort>`_, damit das
Passwort nicht im Klartext auf Ihrer Festplatte gespeichert wird.

.. figure:: media/thunderbird-newaccount-1.png

.. attention::

   Füllen Sie die Felder sorgfältig aus. Das Feld "E-Mail-Adresse"
   **muss** in der Form ``zaXXX@lehrer.uni-karlsruhe.de`` eingegeben
   werden.

Nach wenigen Sekunden hat das Programm die richtigen Einstellungen
gefunden und schlägt Server und Ports für den Empfang und das Senden
von E-Mails vor. Diese Einstellungen sollten mit "Fertig" quittiert
werden.

.. figure:: media/thunderbird-autoconfig.png

Ab jetzt können Sie Ihre E-Mails über IMAP/Port 993 (zwangsläufig über
SSL verschlüsselt) lesen.


E-Mails versenden
=================

.. attention::

   Das Senden von E-Mails über SMTP/Port 465 (zwangsläufig
   verschlüsselt und per Benutzername+Passwort authentifiziert) wird
   zwar gefunden und eingerichtet, funktioniert aber momentan noch
   nicht.



.. 
  Folgende Anleitungen finden Sie hier:
  
  .. toctree::
     :maxdepth: 2 
  
     webmail
     information
     thunderbird
     thunderbird-send


Vorbereitung: Installation SSH/SFTP Programme
=============================================

Sie benötigen für die Anmeldung am Lehrer-Server ein SSH-Programm (zum
Einloggen) und meist auch ein SFTP-Programm (zum Datentransfer). Für
die drei wichtigsten Desktop-Betriebssysteme gibt es hier Links zum
Download von Programmen.


Linux
-----

  * Linux hat SSH-Client-Programme (sogenannte Terminalprogramme)
    immer vorinstalliert. Ebenso ist SFTP-Funktionalität in allen
    gängigen Dateimanagern integriert.
  * Filezilla kann als SFTP-Programm empfohlen werden. Unter Debian/Ubuntu

    .. code-block:: console

       $ sudo apt-get install filezilla
  
Windows
-------

  * SSH-Terminal-Programm `Putty
    <http://www.chiark.greenend.org.uk/~sgtatham/putty/download.html>`_,
    weil es Open Source ist und weit verbreitet.
  * `WinSCP <https://winscp.net/eng/docs/lang:de>`_, weil es Open
    Source ist. Es ist ein SFTP-Programm und enthält auch einfache
    SSH-Terminal-Funktionalität.
  * `ssh.com Cryptonaut
    <https://www.ssh.com/products/ssh-cryptonaut>`_, weil diese Firma
    das zugehörige Protokoll "erfunden" hat und kommerziellen Support
    liefert. Nicht Open Source, hat aber SSH und
    SFTP-Client-Funktionalität in einem Programm.

Mac OS
------
 
  * Mac OS hat ein SSH-Terminal Programm vorinstalliert.   

Linux, Windows & Mac OS
-----------------------

Das SFTP-Programm `Filezilla <https://filezilla-project.org/>`_ ist
Open Source und lässt sich plattformübergreifend nutzen, und wird
daher in folgenden Anleitungen verwendet. Als SSH-Programm
installieren Sie am besten Putty unter Windows.

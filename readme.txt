Installation:

Zur Installation sind alle Dateien entsprechend der Verzeichnisstruktur unterhalb von 'copy_this' ausgehend vom Stammverzeichnis des Shops zu kopieren.
Es wird KEINE EINZIGE DATEI des Oxid eShops �berschrieben, womit auch die Updatef�higkeit gew�hrleistet ist.

In der Datei out\admin\tpl\byte_dashboard_piwik.tpl den iframe von Piwik (zu finden unter Widgets -> Widgetize the full dashboard) an der entsprechenden Stelle einf�gen.
Damit der Button funktioniert muss noch der Link zu Piwik eingef�gt werden.

Da es sich beim Admin-Bereich um einen Passwortgesch�tzen Bereich handelt kann der Piwik-Link mit dem token_auth erweitert werden.
Damit ist eine Anmeldung in Piwik nicht n�tig.


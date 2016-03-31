.. index::
   single: administrace

.. _administrace:

Administrace
------------

Pro práci s nástrojem GeoServer je možné využívat webové GUI, které umožňuje
konfigurovat řadu nastavení serveru. Zejména je možné měnit styly a přidávat nová data.

Jinou možností je využití REST API, které je však vhodné pro pokročilé uživatele.

Uživatelské rozhraní administrace serveru
=========================================

Uživatelské rozhraní je členěno na několik částí. Tyto jsou popsány dále s odkazem na obrázek.
Pro vstup do administrace je nutné se přihlásit. Implicitní uživatelské jemné je admin a heslo geoserver.

.. figure:: images/administrace.png

   Uživatelské rozhraní administrace serveru

About & Status
^^^^^^^^^^^^^^
Sekce umožňující zobrazit informace o stavu serveru, zejména pak log serveru.
Dále je zde možné nastavit základní metadata serveru.

Data
^^^^
Hlavní sekce pro práci se styly a daty.

Services
^^^^^^^^
Sekce umožňující konfiguraci protokolů WMS, WFS a WCS. 

Settings
^^^^^^^^
Sekce pro pokročilé uživatele pro optimalizaci práce s rastrovými daty.

Tile Caching
^^^^^^^^^^^^
Sekce pro konfiguraci kešování obsahu pomocí dlaždic.

Security
^^^^^^^^
Sekce pro konfiguraci uživatelů a práv přístupu.

Demos
^^^^^
Výborná sekce s různými příklady a nástroji.

Tools
^^^^^
Zatím obsahuje pouze nástroj pro nahrání testovacích dat.
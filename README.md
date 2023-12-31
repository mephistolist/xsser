   ![XSSer](https://xsser.03c8.net/xsser/thehive1.png "XSSer")

----------

 + Web: https://xsser.03c8.net

----------

  Cross Site "Scripter" (aka XSSer) is an automatic -framework- to detect, exploit and report XSS vulnerabilities in web-based applications.

  It provides several options to try to bypass certain filters and various special techniques for code injection.

  XSSer has pre-installed [ > 1300 XSS ] attacking vectors and can bypass-exploit code on several browsers/WAFs:

     [PHPIDS]: PHP-IDS
     [Imperva]: Imperva Incapsula WAF
     [WebKnight]: WebKnight WAF
     [F5]: F5 Big IP WAF
     [Barracuda]: Barracuda WAF
     [ModSec]: Mod-Security
     [QuickDF]: QuickDefense
     [Sucuri]: SucuriWAF 
     [Chrome]: Google Chrome
     [IE]: Internet Explorer
     [FF]: Mozilla's Gecko rendering engine, used by Firefox/Iceweasel
     [NS-IE]: Netscape in IE rendering engine mode
     [NS-G]: Netscape in the Gecko rendering engine mode
     [Opera]: Opera Browser

  ![XSSer](https://xsser.03c8.net/xsser/url_generation.png "XSSer URL Generation Schema")

----------

#### Installing:

XSSer runs on many platforms. This install requires FreeBSD, Python 3.9 and you may install its dependencies with the following: 

    doas pkg install py39-pycurl py39-pygeoip pygobject3-common py39-gobject3 py39-cairocffi py39-selenium py39-beautifulsoup py39-setuptools

If you wish to use the GUI version, also run:

    doas pkg install py39-pillow

####  Source libs:

   * Python: https://www.python.org/downloads/
   * PyCurl: http://pycurl.sourceforge.net/
   * PyBeautifulSoup4: https://pypi.org/project/beautifulsoup4/
   * PyGeoIP: https://pypi.org/project/pygeoip/
   * PyGObject: https://pypi.org/project/gobject/
   * PyCairocffi: https://pypi.org/project/cairocffi/
   * PySelenium: https://pypi.org/project/selenium/

----------

####  License:

  XSSer is released under the GPLv3. You can find the full license text
in the [LICENSE](./docs/LICENSE) file.

----------

####  Screenshots:

  ![XSSer](https://xsser.03c8.net/xsser/thehive2.png "XSSer Shell")

  ![XSSer](https://xsser.03c8.net/xsser/thehive3.png "XSSer Manifesto")

  ![XSSer](https://xsser.03c8.net/xsser/thehive4.png "XSSer Configuration")

  ![XSSer](https://xsser.03c8.net/xsser/thehive5.png "XSSer Bypassers")

  ![XSSer](https://xsser.03c8.net/xsser/thehive6.png "XSSer [HTTP GET] [LOCAL] Reverse Exploit")

  ![XSSer](https://xsser.03c8.net/xsser/thehive7.png "XSSer [HTTP POST] [REMOTE] Reverse Exploit")

  ![XSSer](https://xsser.03c8.net/xsser/thehive8.png "XSSer [HTTP DOM] Exploit")

  ![XSSer](https://xsser.03c8.net/xsser/zika4.png "XSSer GeoMap")

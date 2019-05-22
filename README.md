# WebOne
This is a HTTP 1.x proxy that makes old web browsers usable again in the Web 2.0 world.

The proxy should be ran on a modern PC with .NET Framework 4.6 (or newer).
Probably should work in Mono too.

WebOne HTTP Proxy server is working at port 80 and compatible even with Netscape Navigator 3. Set IP (or hostname) of the PC with WebOne as HTTP 1.0 Proxy Server in old browser's settings and begin WWW surfing again. To use an other port, set a shortcut to launch "webone.exe _PORT_" where PORT is a number from 1 to 65535. 

Ready for use binaries are in the __EXE__ folder. There are also a special build for Win2003 or XP (.NET 4.0) called __WebOne-NET4__. But the old .NET from 2010 is impossible to work with modern TLS ciphers and is obsolete like the clients of this proxy.

Note that this app is not intended for daily use, as removing any encryption from web traffic and use of really old and unsupported browser may cause security problems.

### �������� ��-������
__WebOne__ - ������-������ HTTP, ����������� ��������� ����������� ����� �� ������ ���������. �� ������� ���������� HTTPS � ������ ��������� � UTF-8 �� Win. � ������� ����������� �������� ������ ��� �������� � ����� ���������� ����������� ������������� ����������� � ���������� ���������.

���� ������-������ ���������� ��������� �� ����������� �� � .NET Framework 4.6, � ������� IP ����� ����������-������ � ���������� ����������� ���-������������. ���� �� ��������� 80, ��� ������ HTTP 1.0.

� ����� __EXE__ ����������� ��������� ������� ������ ��� Windows 7+. ������������, ��� ������ �������� � � Mono (Linux). ������ "__WebOne-NET4__" ���������� ������������� ��� ������ � .NET 4.0 (Windows XP/2003), �� ��� ����� �� �� ����������� �� ������ � SSL/TLS, ��� � ���������� ���������. Ÿ ������������� �� �������������.

������ ������ ��� �������� �������������� � ����������.
# FAB-team
Cég megnevezése és leírása

Csapat
Név: FAB team 
Csapattagok: Forray Ferenc(PM), Kovács Adrián, Várda Balázs

Cég: Defensys inc.
Leírás: 2025.október 2-án megalakult vállalat, amely mesterséges intelligencián alapuló vírusirtó szolgáltatásokat nyújt. Céljuk, hogy új szintre emeljék a kiberbiztonságot: rendszerük valós időben képes felismerni és semlegesíteni a legújabb fenyegetéseket, még azokat is, amelyek a hagyományos adatbázisokban nem szerepelnek. A cég innovatív megoldásai – mint a prediktív felismerés és a folyamatos tanulás valamint az Ai chat – egyszerre nyújtanak gyors és megbízható védelmet mind lakossági, mind vállalati ügyfeleknek.
A vállalat technológiája nemcsak az ismert vírusok és kártevők felismerésére alkalmas, hanem a gyanús működések és új típusú támadások azonosítására is. Rendszerük folyamatosan tanul, alkalmazkodik a változó fenyegetésekhez, és valós idejű monitorozással segít megelőzni a kibertámadásokat. A cég célja, hogy a mesterséges intelligencia segítségével gyorsabbá, hatékonyabbá és biztonságosabbá tegye a digitális védelmet. 



Épülettervek:

HQ irodaház: 1X router 1X home router 1x firewall ipv4

  HQ routerből irodaház routerbe: 10.0.20.1 255.255.255.0

  HQ routerből datacenter routerbe: 10.0.30.1 255.255.255.0
  
  HQ routerből HQ homerouterbe: 192.168.30.1 255.255.255.0
  
  Protokollok: Ipv4/Ipv6, DHCP, VPN, ACL, DNS, VLAN, Tűzfal, RIP  
  
  Vezetőségi iroda:
  
    HQ routerből vezetőségi irodába: 192.168.10.1 255.255.255.0
    
    eszközök: 4X gép, 1X switch, 1X laptop
  ip kiosztás: DHCP
      
      ethernet csatlakozás asztali számítógépeknek
      vezeték nélküli kapcsolat laptopokhoz, mobilokhoz
      
  Iroda1:
  
      HQ routerből  iroda1-be: 192.168.20.1 255.255.255.0
      
      eszközök: 5X gép, 1X switch
      
      ip kiosztás: DHCP
      ethernet csatlakozás
      vezeték nélküli kapcsolat laptopokhoz, mobilokhoz
   IT szoba:
      
      eszközök: 2X laptop, 1X szerver
      ip kiosztás: DHCP
      vezeték nélküli kapcsolat laptopokhoz, mobilokhoz

Irodaház:  1X router 1X  home router 1x firewall ipv4
       
       Protokollok: Ipv4/Ipv6, DHCP, DNS, VLAN, Tűzfal, OSPF
 iroda1:
 
      Irodaház routerből Iroda1-be: 192.168.40.1 255.255.255.0
      
      eszközök: 4X gép, 1X switch, 1X laptop
      ip kiosztás: DHCP
      ethernet csatlakozás asztali számítógépeknek
      vezeték nélküli kapcsolat laptopokhoz, mobilokhoz
   iroda2:
   
      Irodaház routerből Iroda2-be: 192.168.50.1 255.255.255.0
      eszközök: 5X gép, 1X switch
      ip kiosztás: DHCP
      ethernet csatlakozás
      vezeték nélküli kapcsolat laptopokhoz, mobilokhoz
      
  IT szoba:
  
      Irodaház routerből It szobába: 192.168.60.1 255.255.255.0
      eszközök: 2X laptop, 1X szerver
      ip kiosztás: DHCP
      vezeték nélküli kapcsolat laptopokhoz, mobilokhoz

Datacenter: 1X router 1x firewall 
      
      Protokollok: Ipv4/Ipv6, OSPF, VLAN, Tűzfal, DNS
  Szerverszoba 1:
  
      Datacenter routerből szerverszoba 1-be: 192.168.80.1 255.255.255.0
      Eszközök: 4X szerver, 1X switch
      ip kiosztás: Static
      ethernet csatlakozás
      
  Szerverszoba 2:
  
      Datacenter routerből szerverszoba 2-be: 192.168.90.1 255.255.255.0
      Eszközök: 3X szerver, 1X switch
      ip kiosztás: Static
      ethernet csatlakozás

  Irodaház3: DHCP, Multi layer switch
  
  Iroda1: 
  
  eszközök: 1x switch, server
  ip kiosztás: DHCP
  
 Iroda2:
 
 eszközök: 1x switch, 4x PC
 ip kiosztás: DHCP

 Iroda3:
 
 eszközök: 1x switch, 4x PC
 ip kiosztás: DHCP
 
  

A tervezett protokollok és technológiák listája:
DHCP
OSPF
VLAN
rétegbeli redundancia: van két kábel ugyanazon két switch között.
rétegbeli redundancia: van két különböző router, amelyek ugyanarra a hálózatra vezetnek.
VPN
ACL
DNS
Ipv6 és Ipv4

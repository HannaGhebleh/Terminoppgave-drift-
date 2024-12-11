Slik legger du til DHCP-rollen på en virtuell maskin 💻
1. Installer DHCP-rollen
• Åpne Server Manager.

• Klikk på Add Roles and Features.

• Velg DHCP Server og klikk Install.

2. Lag et nytt område (Scope) 🥄
Åpne DHCP Manager:
• Trykk Win + R, skriv dhcpmgmt.msc og trykk Enter.

Høyreklikk servernavnet og velg New Scope.

Velg:

• IP-område: F.eks. 192.168.1.100 til 192.168.1.200.

• Gateway: F.eks. 192.168.1.1.

• DNS: F.eks. 8.8.8.8.

Klikk finish
3. Autoriser serveren (om nødvendig)✅
Høyreklikk serveren i DHCP Manager.

Velg Authorize.

Refresh.

DHCP klar til å kjøre 🎉

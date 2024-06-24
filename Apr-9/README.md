# PacketTracer Opdracht Readme

## Beschrijving

Deze PacketTracer-opdracht was gericht op het configureren van een netwerkomgeving met behulp van Cisco PacketTracer. Tijdens de opdracht zijn enkele problemen geïdentificeerd en opgelost, waaronder ontbrekende VLAN-configuraties, ontbrekende IP-helperinstellingen en onjuiste kabelaansluitingen.
Problemen

    Ontbrekende VLAN-configuratie: Een VLAN ontbrak in de toegestane VLAN's van de switch.
    Ontbrekende IP-helperinstellingen: De IP-helper was niet ingesteld op Router 1, wat problemen veroorzaakte bij het doorsturen van DHCP-verzoeken.
    Onjuiste kabelaansluitingen: Er waren problemen met de kabelaansluitingen, wat leidde tot connectiviteitsproblemen in het netwerk.

## Oplossingen

    Toevoegen van ontbrekende VLAN: Het ontbrekende VLAN is toegevoegd aan de lijst met toegestane VLAN's op de switch.
    Instellen van IP-helper: De IP-helperinstellingen zijn geconfigureerd op Router 1 om DHCP-verzoeken door te sturen naar de juiste DHCP-server.
    Aanpassen van kabelverbindingen: De kabels zijn correct aangesloten om de connectiviteit tussen apparaten te herstellen.

Oplossingsproces

    VLAN-configuratie: De ontbrekende VLAN-configuratie werd geïdentificeerd door de VLAN's op de switch te controleren en te vergelijken met de vereisten.
    IP-helperinstellingen: Door de DHCP-configuratie op Router 1 te controleren, werd ontdekt dat de IP-helper niet was ingesteld.
    Kabelaansluitingen: Door de fysieke lay-out van de netwerkomgeving te controleren, werden onjuiste kabelaansluitingen geïdentificeerd en aangepast.

## Gebruikte commando,s

        Do show run
        do show ip int br
        sw tr all vl 10,20,30
        ip helper-address 192.168.30.10


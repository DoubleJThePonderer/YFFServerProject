# Server system

## steg en: oppstart
-det første jeg gjør er å skaffe ubuntu på serveren
-etter det er installert så skal jeg fikse ssh å koble till serveren og PC

fredag 4.sep.2026
problemer med å laste ned ubuntu på serveren. 
fikk hjelp til å laste ned ubuntu på serveren via boot menyen f12 under startup
jeg satt enable på ssh på slutten av dagen.

mandag 7.sep.2026
fikk testa ssh og lastet ned ufw med ssh white-lista
må fikse en vei å koble til hjemmenifra med ssh

fredag 11.sep.2026
wifi problemer.
jeg fiksa det med å teste 100 metoder. sikkert en driver oppdatering, og testa med mobilnett. noe fiksa det.
nvm jeg fiksa det ikke
nvm det funker???
funker kablet, kan får ikke lov til å koble hjemmifra.
må jobbe med planlegging og dokumentasjon enmasse

fredag 18.sep.2026
bruker ruter som antenne til Kuben.it.
### følgte denne guiden fra chat gpt til å sette opp:
How to set it up

    Connect the RT-AC51U to your PC with Ethernet.

    Open a browser on the PC and go to the router's administration page, typically:
    192.168.1.1

    Log in.

    Go to Advanced Settings → Wireless → Bridge.

    Select the Wi-Fi band you want to use.

    Under AP Mode, select WDS Only.

    Enable Connect to APs in list.

    Add/select your normal Wi-Fi router's network.

    Enter the Wi-Fi security settings/password if prompted.

    Apply the settings and wait for the RT-AC51U to connect.

ASUS's RT-AC51U manual confirms that WDS Only enables the wireless bridge while preventing other wireless clients from connecting to the RT-AC51U. DDLCDNet

Once connected, leave the Ethernet cable between the RT-AC51U and your PC. Your PC should then get its network connection through the ASUS router.

hadde noen problemer med å sette opp med guiden spør videre
det endte opp å være for mye styr med å bruke ruter som antenne så vi bruker bare kabel med fungerende nett for framtida

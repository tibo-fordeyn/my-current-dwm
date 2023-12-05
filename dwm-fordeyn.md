Dus je werkt morgen verder aan dit bestand, en ik wil enkele zaken verduidelijken over hoe je de scripting zou doen nu ik het net even gedaan heb

Dus je wilt dat eerst wal -i ... gerunt wordt. Dit commando moet volledig worden uitgevoerd voordat de rest van het script kan worden uitgevoerd
Vervolgens moet je uit .cache/wal/colors.sh het eerste kleur nemen, en dit kleur moet ingevoegd worden op lijn 136 van /suckless/config.h, vervolgens moet de terminal gehercompileerd worden met sudo make install
dan moet je hetzelfde doen met de dmenu kleur en dat dan ook hercompilren, dus daarmee bedoel ik dus op regel 13 dat je SchemeSel[2] moet veranderen naar diezeldfe eerste kleur in .cache/wal/colors.sh
Dan op regel 13 die kleur moet veranderd worden door de tweede kleur in dat bestand 
dan run je zathura-pywall -a 0.9
dan run je rogaurance single_static .... script afhankelijk van de kleur 1, niet nul

voor de browser ga je nog moeten kijken hoe dat zit en of er daar nog configuratie voor nodig is.

Vanaf de monitoren werken enzo, ga je hierna ook specifiek voor de hdmi en dan de dp monitor met feh een andere afbeelding toevoegen
dan uiteindelijk moet je nog dat signaal uitsturen om de led lichten aan je bureau van kleur te doen veranderen
dan iets dat ook moeilijk maar doenbaar is is de kleur van de bar veranderen zonder te moeten hercompileren, op dit moment wel nog geen ide hoe dat zou moeten.
en de firmware van je keyboard flashen om dat van kleur te veranderen, wat serieus waarschijnlijk bijna onmogelijk gaat worden

En reset ten slotte alle terminals

pipe alle script met kleuren in dmenu en geef het menu een toets


Als je dat allemaal gedaan hebt dan lijkt het me zo te zijn dat je hele systeem nu perfect van thema is kunnen veranderen. Je kunt dit dan voor bepaalde momenten van de dag automatisch uitvoeren,

Applicaties die misschien extra onderzoek vereisen;
signal in terminal client
neomutt email client
scim


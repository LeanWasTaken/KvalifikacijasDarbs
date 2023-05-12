Initial commit

### Kas vēl jāizdara:
* Statistiku lapām (Gaisa un Augsnes) jāizveido rediģējamas krāsas mērvienībām, piemēram, ja temperatūra ir augstāka par 25C, rādīt sarkanā krāsā. Pagaidām tas viss ir "Hardcoded"
* Jāsakārto Login sistēma. Viss darbojas izņemot error handling. Lietotājam īsti netiek izvadīts kāpēc login neizdevās, vienīgi tas, ka, nu, neizdevās.
* Jāsakārto permission (I guess vienkārši middleware jāpievieno un jāizmanto v-if conditional rendering). Pagaidām pat "Guests" var visu pievienot, dzēst, utt.
* Arduino (ESP8266) koda puse ir vienkārši mess... Vajadzētu pāriet uz WiFiManager plugina, lai vieglāk veikt sākotnējo iestatīšanu (IP Adreses, API URL etc.)

* Tas viss ko 02:06 naktī varu atcerēties.

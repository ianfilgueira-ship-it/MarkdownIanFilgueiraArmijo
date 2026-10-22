5. Observa aquests dos fragments que guarden exactament la mateixa informació sobre tasques quotidianes:

    Opció A (XML):
    <tasques> 
        <tasca estat="completada">
            <descripcio>Posar aigua a bullir</descripcio>
        </tasca>
        <tasca estat="pendent">
            <descripcio>Coure els fideus 3 minuts</descripcio>
        </tasca>
    </tasques>

    Opció B (Markdown):
        - [x] Posar aigua a bullir
        - [ ] Coure els fideus 3 minuts


    a) Quina de les dues opcions és més ràpida d'escriure i més fàcil de llegir per a un humà quan s'obre el fitxer en un editor de text pla sense cap visor?

        El Markdown (opció B), perquè és més fàcil de llegir, més senzill d'escriure i ocupa menys espai.


    b) Si l'Opció B és tan simple, per quina raó un sistema informàtic o una base de dades preferiria rebria/processar la informació en format XML (Opció A) quan s'envien dades entre servidors?

        Perquè XML organitza la informació mitjançant etiquetes i atributs, cosa que facilita que els programes puguin interpretar-la.

    6. Per què creus que Markdown és l'estàndard dels README.md a GitHub?

        Perquè és fàcil d'escriure i llegir, permet organitzar la informació amb títols, llistes, etc. A més, GitHub mostra automàticament el document.

    7. Imagina que estàs buscant una llibreria de codi a GitHub per al teu projecte. Quins beneficis té per a tu com a desenvolupador/a trobar la documentació en un fitxer README.md ben estructurat directament a la portada del repositori en lloc d'un fitxer adjunt en PDF o un document XML?

        Permet entendre ràpidament per a què serveix, com instal·lar-la i com utilitzar-la sense haver de descarregar cap document addicional.

    8. Raona quin format (XML o Markdown) utilitzaries en cadascun d'aquests dos casos reals de DAM/DAW:

        Cas 1: Vols escriure els apunts d'un mòdul o la guia d'instal·lació del teu projecte perquè la llegeixin els teus companys de classe.

            Utilitzaria Markdown, perquè permet organitzar la informació amb títols, llistes, exemples, etc., i és més fàcil de llegir, modificar i compartir.

        Cas 2: Vols crear un fitxer de configuració on una aplicació hagi de llegir les dades dels usuaris de forma estructurada.

            Utilitzaria XML, perquè permet organitzar les dades amb etiquetes i  atributs i facilita que una aplicació les pugui llegir i processar.
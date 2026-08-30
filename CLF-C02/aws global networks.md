Edge Locations (Rampe di ingresso e uscita - On/Off Ramps): Sono centinaia di punti di presenza 
    sparsi nelle principali città del mondo vicini agli utenti finali. Servono per far entrare o 
    uscire rapidamente i dati dall'autostrada privata AWS.

AWS Global Accelerator & S3 Transfer Acceleration (On-ramp): Quando un utente carica un file o 
    invia una richiesta, il traffico entra subito nell'Edge Location più vicina (rampa d'accesso) e 
    percorre l'autostrada privata AWS per raggiungere il server o il bucket S3 di destinazione molto 
    più velocemente.

Amazon CloudFront (Off-ramp / CDN): È la rete per la distribuzione dei contenuti (CDN). Salva copie
    di file, immagini e video direttamente nelle Edge Location per consegnarli all'utente finale alla 
    massima velocità senza dover ogni volta interrogare il server principale.

VPC Endpoints: Consentono alle risorse interne alla tua rete privata virtuale (VPC) di comunicare 
    direttamente con i servizi AWS (come S3 o DynamoDB) rimanendo sempre dentro la rete privata di 
    AWS, senza mai passare per la rete Internet pubblica.


![Global Network](/CLF-C02/zimages/global-network.png)



![alt text](/CLF-C02/zimages/image.png)


    
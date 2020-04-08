# Installazione VirtualBox Windows

La seguente procedura è stata testata su Windows 10 build 1909, ma dovrebbe essere valida per qualunque versione di Windows, con i dovuti accorgimenti.

Cliccate [qui](README-noimg.md) per una versione di questo documento priva di immagini.

## 1. Download

- Scaricare la versione 6.1.4 di VirtualBox da [questo](https://download.virtualbox.org/virtualbox/6.1.4/VirtualBox-6.1.4-136177-Win.exe) link (si tratta del sito ufficiale *virtualbox.org*); a seconda del browser utilizzate, seguire le indicazioni relative:
    * ### Chrome:
        - All'apertura del link il download inizierà automaticamente, e il seguente indicatore verrà mostrato in basso a sinistra della finestra del browser

        ![chrome-01](img/download-chrome-01.PNG)

        - Al termine del download fate click sinistro sul bottone con la freccia verso il basso e selezionate "Apri"

        ![chrome-02](img/download-chrome-02.PNG)

    * ### Edge:
        - All'apertura del link il download NON inizierà automaticamente: cliccate sul bottone "Salva" che comparirà nella finestra di notifica in fondo a quella del browser

        ![edge-01](img/download-edge-01.PNG)

        - Al termine del download fate click sul bottone "Esegui" per avviare l'installazione

        ![edge-02](img/download-edge-02.PNG)

    * ### Firefox:
        - All'apertura del link il download NON inizierà automaticamente: cliccate sul bottone "Salva file" che comparirà nella finestra di dialogo chiamata "Apertura di VirtualBox-6.1.4-136177-Win.exe"

        ![firefox-01](img/download-firefox-01.PNG)

        - Al termine del download fate click sul bottone con la freccia verso il basso, che si trova in alto a destra del browser

        ![firefox-02](img/download-firefox-02.PNG)

        - Cliccate col tasto sinistro sul nome del file appena scaricato ("VirtualBox-6.1.4-136177-Win")

        ![firefox-03](img/download-firefox-03.PNG)

## 2. Installazione

**NOTA**: per l'installazione del programma VirtualBox sono necessari 500MB di spazio libero sul disco, oltre a 20 GB di spazio libero per importare ed utilizzare correttamente la macchina virtuale fornita per il corso.

- Avviare il file di installazione e seguire la procedura illustrata di seguito:
    * Cliccare "Avanti >" sulla schermata di benvenuto;

    ![vbox-01](img/install-vbox-01.PNG)

    * Cliccare "Avanti >" sulla prima schermata **Installazione personalizzata**;

    ![vbox-02](img/install-vbox-02.PNG)

    * Cliccare "Avanti >" sulla seconda schermata **Installazione personalizzata**;

    ![vbox-03](img/install-vbox-03.PNG)

    * Cliccare "Si" sulla schermata **Avviso: Interfacce di rete**;

    ![vbox-04](img/install-vbox-04.PNG)

    * Cliccare "Installa" sulla schermata **Pronto per l'installazione**

    ![vbox-05](img/install-vbox-05.PNG)

- Consentire al programma di effettuare modifiche al PC, per avviare la procedura di installazione (l'avviso di UAC di Windows comparirà dopo qualche secondo dal click sul bottone "Installa");

    ![vbox-06](img/install-vbox-06.PNG)

---
- Cliccare "Installa" sulla finestra **Installare questo software di dispositivo?** per quanto riguarda il software `Oracle Corporation Controller USB ...`;
---


- Cliccare "Fine" sulla schermata **L'installazione di Oracle VM Virtualbox 6.1.4 è completata**; il programma verrà avviato.

    ![vbox-07](img/install-vbox-07.PNG)

## 3. Importare la macchina virtuale

Il file che contiene tutto il necessario per utilizzare la macchina virtuale proposta (chiamato `RH024.ova`) è disponibile al seguente [link](https://drive.google.com/drive/folders/1c4IuzkvrNeV_sK_EpQOL70isygrPNdc1?usp=sharing); dopo aver cliccato il link, fate riferimento al [passo 1](#1-download) per quanto riguarda il download e l'apertura del file.

- Una volta scaricato il file, apritelo in VirtualBox (se avete seguito la procedura di installazione proposta, basterà un doppio click):

![import-01](img/import-ova-01.PNG)

- Cliccare su "Importa" nella finestra di riepilogo che apparirà:

![import-02](img/import-ova-02.PNG)

- Attendere che l'importazione sia terminata, a questo punto la macchina virtuale sarà disponibile come una voce nell'elenco della finestra di VirtualBox:

![import-03](img/import-ova-03.PNG)
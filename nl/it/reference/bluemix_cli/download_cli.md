---



copyright:

  years: 2015, 2018
lastupdated: "2018-07-09"

---

{:codeblock: .codeblock}
{:shortdesc: .shortdesc}
{:new_window: target="_blank"}
{:tip: .tip}


# Installazione della CLI {{site.data.keyword.Bluemix_notm}} autonoma
{: #install_use}

La CLI {{site.data.keyword.Bluemix_notm}} fornisce l'interfaccia della riga di comando per gestire applicazioni, contenitori, infrastrutture, servizi e altre risorse in {{site.data.keyword.Bluemix_notm}}.

Se vuoi installare la CLI {{site.data.keyword.Bluemix}} e altri plug-in e strumenti consigliati per lo sviluppo di applicazioni per {{site.data.keyword.Bluemix_notm}}, segui il metodo descritto [qui](/docs/cli/index.html).
{: tip}

Utilizza la seguente procedura per installare la CLI {{site.data.keyword.Bluemix_notm}} autonoma:

1. Seleziona il programma di installazione del tuo sistema operativo per il download

   Mac OS X a 64 bit: [programma di installazione](https://clis.ng.bluemix.net/download/bluemix-cli/latest/osx){: new_window} / [sha1sums](https://clis.ng.bluemix.net/download/bluemix-cli/latest/osx/checksum){: new_window} <br>
   Windows a 64 bit: [programma di installazione](https://clis.ng.bluemix.net/download/bluemix-cli/latest/win64){: new_window} / [sha1sums](https://clis.ng.bluemix.net/download/bluemix-cli/latest/win64/checksum){: new_window} <br>
   Linux X86 a 64 bit: [programma di installazione](https://clis.ng.bluemix.net/download/bluemix-cli/latest/linux64){: new_window} / [sha1sums](https://clis.ng.bluemix.net/download/bluemix-cli/latest/linux64/checksum){: new_window} <br>
   Linux LE a 64 bit (ppc64le): [installer](https://clis.ng.bluemix.net/download/bluemix-cli/latest/ppc64le){: new_window} / [sha1sums](https://clis.ng.bluemix.net/download/bluemix-cli/latest/ppc64le/checksum){: new_window} <br>

   **Le release a 32 bit e le versioni precedenti sono disponibili [qui](all_versions.html)

1. Esegui il programma di installazione
   * Per macOS e Windows, esegui solo il programma di installazione.
   * Per Linux, estrai il pacchetto ed esegui lo script `install_bluemix_cli`

1. Punta a un endpoint API ed esegui l'accesso a {{site.data.keyword.Bluemix_notm}}

  ![Esempio](example.gif){: gif}

Ora sei pronto a gestire le risorse {{site.data.keyword.Bluemix_notm}}. Immetti `ibmcloud help` per visualizzare le descrizioni dei comandi.

Se stai utilizzando un ID federato, segui le istruzioni [qui](https://console.bluemix.net/docs/iam/login_fedid.html#federated_id) per accedere con un passcode monouso o una chiave API.  
{: tip}

## Ulteriori opzioni per installare la CLI {{site.data.keyword.Bluemix_notm}}
{: #more_options_install}


Oltre al [programma di installazione](install_use_cli.html#getting_started), puoi utilizzare anche la shell per scaricare e installare la CLI. 


### Installa dalla shell
{: #shell_install}


### MacOS

Copia e incolla il seguente comando in un terminale del tuo SO Mac ed eseguilo:

```
curl -fsSL https://clis.ng.bluemix.net/install/osx | sh
```
{: codeblock}

### Linux

Copia e incolla il seguente comando in un terminale del tuo SO Linux ed eseguilo:

```
curl -fsSL https://clis.ng.bluemix.net/install/linux | sh
```
{: codeblock}

### Windows PowerShell

Copia e incolla il seguente comando in una console del terminale [Windows PowerShell](https://msdn.microsoft.com/en-us/powershell/scripting/getting-started/getting-started-with-windows-powershell){: new_window} ed eseguilo:

```
iex(New-Object Net.WebClient).DownloadString('https://clis.ng.bluemix.net/install/powershell')
```
{: codeblock}

## Altri link per esplorare ulteriormente la CLI {{site.data.keyword.Bluemix_notm}}

* [Amplia le funzionalità della CLI {{site.data.keyword.Bluemix_notm}} con i plugin](/docs/cli/reference/bluemix_cli/extend_cli.html)
* [Utilizzo dei comandi della CLI {{site.data.keyword.Bluemix_notm}} generali](/docs/cli/reference/bluemix_cli/bx_cli.html)
* [Utilizzo dei comandi {{site.data.keyword.Bluemix_notm}} (ibmcloud sl) generali](/docs/cli/reference/softlayer/index.html)


## Segnala problemi e inoltra un feedback
{: #issues}

Utilizza le seguenti opzioni per segnalare problemi o inoltrare richieste di nuove funzioni:
 * Crea i problemi in [Github](https://github.com/IBM-Bluemix/bluemix-cli-release/issues){: new_window} ![Icona link esterno](../../../icons/launch-glyph.svg)
 * Lascia dei messaggi nel [canale Slack ](https://dwopen.slack.com/messages/bluemix-cli/){: new_window} ![Icona link esterno](../../../icons/launch-glyph.svg)

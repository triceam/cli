---



copyright:

  years: 2015, 2018
lastupdated: "2018-06-27"

---

{:codeblock: .codeblock}
{:shortdesc: .shortdesc}
{:new_window: target="_blank"}
{:tip: .tip}


# Installation de l'interface de ligne de commande {{site.data.keyword.Bluemix_notm}} autonome
{: #install_use}

L'interface de ligne de commande {{site.data.keyword.Bluemix_notm}} fournit l'interface de ligne de commande permettant de gérer des applications, des conteneurs, des infrastructures, des services et d'autres ressources dans {{site.data.keyword.Bluemix_notm}}.

Si vous souhaitez installer l'interface de ligne de commande {{site.data.keyword.Bluemix}} ainsi que d'autres outils et plug-in recommandés pour le développement d'applications pour {{site.data.keyword.Bluemix_notm}}, suivez la méthode décrite [ici](/docs/cli/index.html).
{: tip}

Procédez comme suit pour installer l'interface de ligne de commande {{site.data.keyword.Bluemix_notm}} autonome :

1. Sélectionnez le programme d'installation de votre système d'exploitation afin de le télécharger

   Mac OS X 64 bits : [installer](https://clis.ng.bluemix.net/download/bluemix-cli/latest/osx){: new_window} / [sha1sums](https://clis.ng.bluemix.net/download/bluemix-cli/latest/osx/checksum){: new_window} <br>
   Windows 64 bits : [installer](https://clis.ng.bluemix.net/download/bluemix-cli/latest/win64){: new_window} / [sha1sums](https://clis.ng.bluemix.net/download/bluemix-cli/latest/win64/checksum){: new_window} <br>
   Linux X86 64 bits : [installer](https://clis.ng.bluemix.net/download/bluemix-cli/latest/linux64){: new_window} / [sha1sums](https://clis.ng.bluemix.net/download/bluemix-cli/latest/linux64/checksum){: new_window} <br>
   Linux LE 64 bits (ppc64le) : [installer](https://clis.ng.bluemix.net/download/bluemix-cli/latest/ppc64le){: new_window} / [sha1sums](https://clis.ng.bluemix.net/download/bluemix-cli/latest/ppc64le/checksum){: new_window} <br>

   **Les éditions 32 bits et les versions antérieures sont disponibles [ici](all_versions.html).

1. Exécutez le programme d'installation
   * Pour Mac OS et Windows, exécutez simplement le programme d'installation.
   * Pour Linux, procédez à l'extraction du contenu du package et exécutez le script `install_bluemix_cli`.

1. Ciblez un noeud final d'API et connectez-vous à {{site.data.keyword.Bluemix_notm}}

  ![Exemple](example.gif){: gif}

Vous êtes maintenant prêt à gérer des ressources {{site.data.keyword.Bluemix_notm}}. Entrez `ibmcloud help` pour examiner les descriptions des commandes.

Si vous utilisez un ID fédéré, suivez les instructions décrites [ici](https://console.bluemix.net/docs/iam/login_fedid.html#federated_id) pour vous connecter avec un code d'accès unique ou une clé d'API.  
{: tip}

## Autres options d'installation de l'interface de ligne de commande {{site.data.keyword.Bluemix_notm}}
{: #more_options_install}


Outre le [programme d'installation](install_use_cli.html#getting_started), vous pouvez également utiliser le shell pour télécharger et installer l'interface de ligne de commande. 


### Installation à partir du shell
{: #shell_install}


### MacOS

Copiez et collez la commande suivante dans un terminal de votre système Mac OS et exécutez-la :

```
curl -fsSL https://clis.ng.bluemix.net/install/osx | sh
```
{: codeblock}

### Linux

Copiez et collez la commande suivante dans un terminal de votre système Linux OS et exécutez-la :

```
curl -fsSL https://clis.ng.bluemix.net/install/linux | sh
```
{: codeblock}

### Windows PowerShell

Copiez et collez la commande suivante dans une console de terminal [Windows PowerShell](https://msdn.microsoft.com/en-us/powershell/scripting/getting-started/getting-started-with-windows-powershell){: new_window} et exécutez-la :

```
iex(New-Object Net.WebClient).DownloadString('https://clis.ng.bluemix.net/install/powershell')
```
{: codeblock}

## Autres liens permettant d'explorer davantage l'interface de ligne de commande {{site.data.keyword.Bluemix_notm}}

* [Extension de l'interface de ligne de commande {{site.data.keyword.Bluemix_notm}} avec des plug-in](extend_cli.html)
* [Document sur l'utilisation des commandes de l'interface de ligne de commande {{site.data.keyword.Bluemix_notm}}](ic_cli_cmds.html)


## Signaler des problèmes et soumettre des commentaires en retour
{: #issues}

Utilisez les options suivantes pour signaler des problèmes ou soumettre des demandes de nouvelle fonction :
 * Signalez des problèmes dans [Github](https://github.com/IBM-Bluemix/bluemix-cli-release/issues){: new_window} ![Icône de lien externe](../../../icons/launch-glyph.svg)
 * Laissez des messages sur le [canal Slack](https://dwopen.slack.com/messages/bluemix-cli/){: new_window} ![Icône de lien externe](../../../icons/launch-glyph.svg)

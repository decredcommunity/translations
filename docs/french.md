# Decred Translation

This document aims to serve as a reference to translate Decred software to french.
It contains key translation resources that can be used for translation activity and contains translation of most commons technical terms encountered.

# Translation Resources
* Legifrance "Journal officiel - Vocabulaire de l'informatique et des actifs numériques"

  Vocabulaire de l'informatique (2017): https://www.legifrance.gouv.fr/download/pdf?id=IrBXhCNAI5OYr7F-Idzjo3QThGDlKNNq4H-vAba4fMw

  Vocabulaire des actifs numériques (2021): https://www.legifrance.gouv.fr/download/pdf?id=faoNbIDIFbjBr3IBpEk1O3caoaKmU8eluFBKkf289nc
  
* OQLF - Office quebecois de la langue française : http://gdt.oqlf.gouv.qc.ca

* The french translation of "Mastering Bitcoin (Andreas M. Antonopoulos)" : "[Au coeur du Bitcoin - Programmer la Blockchain ouverte](https://www.oreilly.com/library/view/au-cur-du/9782412037454/)"
* [bitcoin.fr](https://www.bitcoin.fr) articles and knowledge base
* The french translation of [Phoenix LN mobile app](https://github.com/ACINQ/phoenix)
* wikipedia.fr

# Technical terms Translation

The following table contains technical terms and their equivalent in french, the source that influenced the decision and eventually remarks associated.

| Term | Translation                                | Source | Remarks |
|----|--------------------------------------------|---|----|
|blockchain | la blockchain                              |Mastering Bitcoin Translation, bitcoin.fr, various french media|"chaîne de blocs" is recommended by Legifrance and OQLF, but most of people actually use "La blockchain" and that's why it has been chosen. It should be changed to "chaîne de blocs" if it starts to be used by people. |
|coinbase| coinbase                                   |Mastering Bitcoin translation||
|coin| jeton                                      |Legifrance|
|wallet| portefeuille                               |Mastering Bitcoin translation|
|proof-of-work | preuve de travail                          |legifrance, oqlf, Mastering Bitcoin translation|
|PoW | PdT/PoW                                    ||
|proof-of-stake | preuve d'enjeu                             | bitcoin.fr, oqlf|
|PoS | PdE/PoS                                    ||
|off-chain| hors chaîne                                |Mastering Bitcoin translation|
|on-chain | sur la chaîne                              |Mastering Bitcoin translation|
|seed| graine                                     |Mastering Bitcoin translation|
|unspent transaction output| sortie de transaction non dépensée         |Mastering Bitcoin translation |
|daemon| daemon                                     |wikipedia.fr|technical term in software engineering must not be translated as "démon"|
|mempool| mempool                                    |Mastering Bitcoin translation|
|passphrase| phrase secrète                             |wikipedia.fr, oqlf|
|staking| staking                                    | |No clear french word equivalent found|
|stake| stake                                      |enjeu (stake)||
|staker| staker                                     | |No clear french word equivalent found|
|stakeholder| stakeholder                                | |No clear french word equivalent found|
|stakepool| stakepool                                  | |No clear french word equivalent found|
|ticket buyer| acheteur de ticket                         ||
|ticketpool| ticketpool                                 | |No clear french word equivalent found|
|voting authority| droits de vote                             | |"droits de vote" is closer to the meaning|
|autobuyer| achat automatisé     ||
|spv| spv ou vérification de paiement simplifiée |Mastering Bitcoin translation|
|lightning-network | lightning-network                          |bitcoin.fr |
|channel point| point de canal                             | |Translated literally but a better translation may be found|
|invoice LN| Demande de paiement LN                     |Phoenix LN mobile app translation |
|watchtower| watchtower                                 |bitcoin.fr|
|timelock| verrou temporel                            |bitcoin.fr|

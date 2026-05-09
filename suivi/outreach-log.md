# Outreach Log - Focale

**Date:** 2026-05-08 (UTC)  
**Campaign:** Email 1 - J1 + relance courte J5  
**Prospects source:** `prospection/prospects-focale-suisse-romande.md`  
**Sequence source:** `emails/SEQUENCE_EMAIL_PME_FOCALE.md`  
**Template J5 execute:** `emails/J5_relance.md`

## Resume

- **Emails J1 envoyes:** 4
- **Emails J5 attendus:** 4
- **Emails J5 effectivement envoyes:** 12
- **Contacts verifies disponibles dans la source:** 4
- **Objet J5 de base demande:** `Une question rapide`
- **Expediteur demande:** `sf@experientiel.ch`
- **Expediteur reel utilise par NanoCorp:** `emprova@nanocorp.app`
- **CTA principal utilise:** `https://focale.experientiel.ch/` puis cliquer sur `Acces demo`
- **CTA secondaire utilise:** repondre a `sf@experientiel.ch` pour une demo presentielle

## Note importante sur la conformite

NanoCorp a envoye les messages depuis `emprova@nanocorp.app` et a ajoute automatiquement un footer HTML mentionnant `https://emprova.nanocorp.app`. J'ai verifie auparavant que l'override `from` n'est pas pris en charge par l'interface CLI exposee.

## Incident d'execution J5

L'intention etait d'envoyer 1 relance J5 par contact, en reponse au J1 via `--reply-to`. Pendant la capture des reponses JSON NanoCorp, deux tentatives shell ont partiellement abouti avant de bloquer sur le traitement local, puis une troisieme tentative a ete executee proprement. Resultat reel cote NanoCorp: **3 envois J5 par contact**, soit **12 emails sortants** au total. Aucun envoi supplementaire n'a ete fait apres verification de `nanocorp emails list`.

## Suivi par contact

| Prospect | Entreprise | Email | J1 Sujet envoye | J1 Email ID | J1 Envoye le (UTC) | J5 Sujet envoye | J5 Email IDs | J5 Envoye le (UTC) | J5 Statut |
|---|---|---|---|---|---|---|---|---|---|
| Allen Vernier | TMR - Transports de Martigny et Regions | `allen.vernier@tmrsa.ch` | `Allen, comment mesurez-vous vraiment le vecu collaborateur chez TMR ?` | `9cff0e58-57e1-473f-b42d-012fb6ea0a69` | `2026-05-07T02:18:17.249257` | `Allen, une question rapide` | `4e4a5171-b058-4556-b780-6b595f1231d9`; `2ee30fe1-92f9-4408-b2bc-1e308f5d2551`; `c025b09a-de17-4eee-ab49-84161b951280` | `2026-05-08T02:43:15.126463`; `2026-05-08T02:43:39.688865`; `2026-05-08T02:43:54.465418` | Envoye x3 |
| Hugues Jeanbourquin | Schaublin Machines SA | `h.jeanbourquin@smsa.ch` | `Hugues, avez-vous une vision claire de l\experience collaborateur chez Schaublin Machines SA ?` | `3d112b75-bf8a-4b4d-8f65-d060f519ced8` | `2026-05-07T02:18:20.612673` | `Hugues, une question rapide` | `0c4e3003-b6b9-45d2-9a26-965a08bcd64d`; `69e211c4-abb8-4248-9740-b73e8e1406e5`; `cd9c2fbe-4b58-493a-b4f3-8c78c2916fea` | `2026-05-08T02:43:18.989309`; `2026-05-08T02:43:43.776755`; `2026-05-08T02:43:58.581979` | Envoye x3 |
| Marc Dutoit | HSE Conseils SA | `marc.dutoit@hseconseils.ch` | `Marc, comment savoir si vos actions RH changent vraiment quelque chose ?` | `7df18f43-a617-4b7e-b135-c7a79b3a60dd` | `2026-05-07T02:18:24.236601` | `Marc, une question rapide` | `36082749-d1c2-49bb-bb3d-1648e90cc20e`; `4fb471d1-056d-446e-babc-ef6fe38ce77c`; `043c0e6b-2afa-4a26-b3ad-bf55b6587748` | `2026-05-08T02:43:23.341397`; `2026-05-08T02:43:47.781123`; `2026-05-08T02:44:02.801975` | Envoye x3 |
| Christophe Bizzini | SCI-Services SA | `christophe.bizzini@sci-services.ch` | `Christophe, comment vivent vraiment vos equipes chez SCI-Services SA ?` | `1aa24dd1-bf7d-4904-80e7-fad7faf7ef58` | `2026-05-07T02:18:27.669375` | `Christophe, une question rapide` | `b47eae97-0c24-435c-a6a4-783e9051cffb`; `faaaea39-d07a-4f93-a2f2-1f3b6b53997c`; `2bef3600-8541-4a6b-a126-b0403c398796` | `2026-05-08T02:43:27.407269`; `2026-05-08T02:43:52.193338`; `2026-05-08T02:44:06.984853` | Envoye x3 |

## Personnalisation appliquee

- Prenom personnalise dans l'objet et l'ouverture
- Threading J5 sur le message J1 via `--reply-to`
- Question unique centree sur la mesure de l'impact des decisions RH
- Signature `Focale par Experientiel Sarl / Stephane Fellay / sf@experientiel.ch`

---

## Campagne 2026-05-08 - J1 Groupe C batch 1

**Date:** `2026-05-08` (UTC)  
**Campaign:** Email 1 - J1 Groupe C batch 1  
**Prospects source:** `prospection/DOSSIER_PROSPECTION_MANUEL.md`  
**Template J1 execute:** `emails/J1_introduction.md`

### Resume

- **Selection appliquee:** 5 premiers contacts du Groupe C avec domaine explicite (`#3` a `#7`)
- **Verifications NanoCorp executees:** 5
- **Emails verifies:** 4
- **Emails non verifies:** 1
- **Emails J1 envoyes:** 4
- **Expediteur reel utilise par NanoCorp:** `emprova@nanocorp.app`
- **CTA principal utilise:** `focale.experientiel.ch` puis cliquer sur `Acces demo`
- **CTA secondaire utilise:** contacter `sf@experientiel.ch` pour une demo en presentiel en Suisse Romande

### Suivi par contact

| Prospect | Entreprise | Email probable | Email verifie | Statut verification | J1 Sujet envoye | J1 Email ID | J1 Envoye le (UTC) | Statut envoi |
|---|---|---|---|---|---|---|---|---|
| Mauro Ambrosini | Stoco SA | `m.ambrosini@stoco.ch` | `mambrosini@stoco.ch` | Verifie | `Mauro, vos collaborateurs - vous en avez une image claire ?` | `ccbf7b86-dc10-4a2f-84ae-546d71f8deb2` | `2026-05-08T02:56:31.666313` | Envoye |
| Carlos Convers | Jean-Francois Baud SA | `c.convers@jfbaud.ch` | `-` | Non verifie | `-` | `-` | `-` | Non envoye |
| Alain Hess | MIMOTEC SA | `a.hess@mimotec.ch` | `alain.hess@mimotec.ch` | Verifie | `Alain, vos collaborateurs - vous en avez une image claire ?` | `fa0d989b-3cab-4bc0-a550-d8e529de869b` | `2026-05-08T02:56:35.580599` | Envoye |
| Emilie Rebetez | easyDec SA | `e.rebetez@easydec.ch` | `emilie.rebetez@easydec.ch` | Verifie | `Emilie, vos collaborateurs - vous en avez une image claire ?` | `61bccffa-20b5-4583-bb65-4128dc0b5425` | `2026-05-08T02:56:39.030192` | Envoye |
| Alain Codourey | Asyril SA | `a.codourey@asyril.com` | `alain.codourey@asyril.com` | Verifie | `Alain, vos collaborateurs - vous en avez une image claire ?` | `8149c0d3-afd9-46fc-b8c1-fb25994a78a9` | `2026-05-08T02:56:42.391081` | Envoye |

### Notes

- La verification NanoCorp a retourne des adresses reelles differentes du format initial pour `Stoco SA`, `MIMOTEC SA`, `easyDec SA` et `Asyril SA`.
- La verification de `Carlos Convers / Jean-Francois Baud SA` n'a retourne aucune adresse et n'a donc produit aucun envoi.
- Le template J1 local etait absent du repo; il a ete cree avant execution sous `emails/J1_introduction.md`.

---

## Campagne 2026-05-09 - J1 hotellerie et sante

**Date:** `2026-05-09` (UTC)  
**Campaign:** Email 1 - J1 hotellerie et sante  
**Prospects source:** `prospection/LISTE_PROSPECTS_CONSOLIDEE.md`  
**Template J1 execute:** `emails/J1_introduction.md`

### Resume

- **Contacts prets identifies dans la source:** 6
- **Verification anti-doublon dans `suivi/outreach-log.md`:** 6/6 non contactes
- **Verification anti-doublon dans NanoCorp outbound:** 6/6 absents des 100 derniers emails sortants
- **Emails J1 envoyes:** 6
- **Expediteur reel utilise par NanoCorp:** `emprova@nanocorp.app`
- **CTA principal utilise:** `focale.experientiel.ch` puis cliquer sur `Acces demo`
- **CTA secondaire utilise:** contacter `sf@experientiel.ch` pour une demo en presentiel en Suisse Romande

### Suivi par contact

| Prospect | Entreprise | Email | Statut email | J1 Sujet envoye | J1 Email ID | J1 Envoye le (UTC) | Statut envoi |
|---|---|---|---|---|---|---|---|
| Daisy Gros | BERTOLIT SA | `daisy.gros@bertolit.ch` | confirme | `Daisy, avez-vous une vision claire du vecu collaborateur chez BERTOLIT SA ?` | `f213b22e-104c-414f-b60d-0dc4801d6312` | `2026-05-09T02:50:35.625222` | Envoye |
| Yves Defalque | Hotel Vatel Martigny | `y.defalque@vatel.ch` | confirme | `Yves, avez-vous une vision claire du vecu collaborateur chez Hotel Vatel Martigny ?` | `fc58b352-7428-40cf-941e-532e4492ba99` | `2026-05-09T02:50:37.840929` | Envoye |
| Maryline D'Amario | CIPOSA SA | `mdamario@ciposa.com` | probable | `Maryline, avez-vous une vision claire du vecu collaborateur chez CIPOSA SA ?` | `58bc4361-d2a5-475b-8b05-a3eaae0e5b71` | `2026-05-09T02:50:40.022140` | Envoye |
| Jeremie Laurent | Hotel d'Angleterre | `jlaurent@dangleterrehotel.com` | probable | `Jeremie, avez-vous une vision claire du vecu collaborateur chez Hotel d'Angleterre ?` | `41a9a269-684e-438a-bba1-75081b5d6870` | `2026-05-09T02:50:42.182104` | Envoye |
| Florence Rabaud | Hotel d'Angleterre | `frabaud@dangleterrehotel.com` | probable | `Florence, avez-vous une vision claire du vecu collaborateur chez Hotel d'Angleterre ?` | `a64fb28d-c6d2-4a50-abbe-66e3131d0c70` | `2026-05-09T02:50:44.401219` | Envoye |
| Laurence Voegelin-Stamm | Hotel Beaulac | `stamm@beaulac.ch` | probable | `Laurence, avez-vous une vision claire du vecu collaborateur chez Hotel Beaulac ?` | `176f2642-6f47-422e-b853-642ed985be2f` | `2026-05-09T02:50:46.479442` | Envoye |

### Notes

- Le template J1 a ete aligne avant execution avec le CTA demande et la signature complete de Stephane Fellay.
- Les emails ont ete envoyes sequentiellement pour garantir un seul envoi par contact.

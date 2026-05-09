# NanoCorps — Documentation opérationnelle

## Aperçu

Ce dépôt regroupe les actifs de prospection Focale:
- `prospection/` pour les listes de prospects
- `emails/` pour les templates d'emails
- `suivi/` pour les statuts et journaux d'envoi
- `strategie/` pour les documents d'analyse

## Exploration initiale — 2026-05-09

- Le dépôt externe cloné depuis `experientiel-ch/NanoCorps` ne contenait pas encore de `DOCS.md`.
- Le brief mentionne `suivi/outreach-log.md`, mais le dépôt ne contenait que `suivi/tableau_suivi.md`.
- Le dépôt contient déjà un template de dernier contact sous `emails/J12_contact_final.md`, mais il ne correspond pas exactement à la demande opérationnelle du jour:
  - objet différent
  - corps orienté "analyse ponctuelle CHF 2'500"
  - pas de formulation "Je ferme votre dossier"
- Les 4 prospects concernés et leurs emails confirmés sont présents dans `prospection/LISTE_PROSPECTS_CONSOLIDEE.md`:
  - Allen Vernier — `allen.vernier@tmrsa.ch`
  - Hugues Jeanbourquin — `h.jeanbourquin@smsa.ch`
  - Marc Dutoit — `marc.dutoit@hseconseils.ch`
  - Christophe Bizzini — `christophe.bizzini@sci-services.ch`
- Leur statut avant exécution:
  - J1 envoyé le 2026-05-07
  - J5 envoyé le 2026-05-08
  - J12 envoyé: non
- Vérification NanoCorp avant envoi:
  - aucun email sortant avec l'objet `Je ferme votre dossier` n'a été trouvé pour ces 4 destinataires
  - les 4 destinataires ont déjà un historique J1 puis J5

## Changements de structure prévus pour cette tâche

- Créer `emails/J12_breakup.md` comme template J12 demandé.
- Créer `suivi/outreach-log.md` pour centraliser l'historique J1, J5 et J12.
- Mettre à jour les statuts dans `suivi/tableau_suivi.md` et `prospection/LISTE_PROSPECTS_CONSOLIDEE.md`.

## Exécution J12 — 2026-05-09

- Template créé:
  - `emails/J12_breakup.md`
- Journal créé:
  - `suivi/outreach-log.md`
- Envois J12 effectués via `nanocorp emails send`, un seul envoi par contact, avec threading sur le dernier J5 connu:
  - Allen Vernier — `49f24a6b-4e8e-478e-b9f6-bdb7af0d61b5` — `2026-05-09T02:46:03.851724`
  - Hugues Jeanbourquin — `b9a24896-3cc2-49fd-901f-c08ebc02a15c` — `2026-05-09T02:46:06.381775`
  - Marc Dutoit — `6a448f58-76b1-47c4-96ae-4d2651bb166b` — `2026-05-09T02:46:08.762036`
  - Christophe Bizzini — `c78cb42d-1ecb-42cd-a99b-ca2e02a17d51` — `2026-05-09T02:46:11.236845`
- Vérification post-envoi:
  - les 4 emails apparaissent dans `nanocorp emails list --direction outbound`
  - objet confirmé pour chacun: `Je ferme votre dossier`
- Fichiers métier synchronisés après envoi:
  - `suivi/outreach-log.md`
  - `suivi/tableau_suivi.md`
  - `prospection/LISTE_PROSPECTS_CONSOLIDEE.md`

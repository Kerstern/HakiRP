# Serveur

Ce que j'ai déjà :

- Loginscreen


#TODO List

1. Sauvegarde des coordonnées et respawn au même endroit
2. Loadouts suivant un certain niveau de permission (policiers, pompiers, médecins)
3. Banque
4. Métiers (taxi, bus, poubelles, mineur)
5. Menu général (plus de commandes) (ID, téléphone, actions)
6. Fonctions de policiers, médecins (menottes, heal, voir idendité, drag)
7. Activités ? (drogue, braquage, stripclub...)



#Métiers :

- Taxi
- Bus
- Policier
- Médecin
- Pompier
- Dépanneur
- Fourgon blindé (Amener de l'argent de la banque aux différents ATM)
- Mineur

#Banque :

- Déposer argent
- Retirer argent
- Sauvegarder argent dans DB


#Pole-emploi :

- Prendre un job
- Recevoir une paye toutes les 10min
- Ne pas pouvoir prendre d'autre job sans démissionner



    sessionsFound
    Params: sessions

sessionJoining
Params: cur, max, hostName

sessionJoined
Params:

sessionJoinFailed
Params:

sessionHostFailed
Params: err

sessionHosted
Params:

sessionInitialized
Params:

sessionStateChanged
Params: state

getResourceInitFuncs
Params: isPreParse, add

onClientResourceStart
Params: res

onClientResourceStop
Params:

onResourceStop
Params: name

playerActivated
Params:

playerDropped
Params:

onPlayerJoining
Params: netId, name

onPlayerKilled
Params: playerId, attackerId, reason, position

onPlayerDied
Params: playerId, reason, position

onClientMapStart
Params:

onClientMapStop
Params:

onMapStart
Params:

getMapDirectives
Params: add

onClientGameTypeStart
Params:

------------------------ RegisterServerEvent ---------------------------

playerSpawned (in spawnmanager?)
Params:

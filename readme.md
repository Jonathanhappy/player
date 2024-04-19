# Track Payer Audio

## Acteurs du système :

- Utilisateurs grand public

## Services :

- service Player : lire le fichier .mp3

## Cas d'utilisation :
- Un utilisateur peut lire lien (point de montage .mp3) en appuiant sur play et le passe en mode to pause
- En appuiant sur pause il fait un reset qui reinitialise le buffer et stop le player et repasse en mode to play

## API Design
### EndPoints
#### a - Utilisateur
- `/api/v1/users/sound.mp3 :` Endpoint source audio

## Technologie
- React Native

![react native.png](resources%2Freact%20native.png)

- React Native Track Player

![react native track player.png](resources%2Freact%20native%20track%20player.png)

## UI design

<img alt="screen01.png" height="200" src="resources%2Fscreen01.png" width="150"/>

<img alt="screen02.png" height="200" src="resources%2Fscreen02.png" width="150"/>

<img alt="screen03.png" height="200" src="resources%2Fscreen03.png" width="150"/>

<img alt="screen04.png" height="200" src="resources%2Fscreen04.png" width="150"/>
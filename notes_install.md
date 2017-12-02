# Installation Raspberry

## Matériel nécessaire

- Raspberry
- alimentation
- carte micro SD

- Internet
- Hatcher

## Mode opératoire

- Télécharger l'image Screen42
- Installer Etcher [site](https://etcher.io/)
- Lancer Etcher
  - selectionner image
  - selectionner la carte microSD
  - flasher la carte
- réinsérer la carte microSD
- créer un fichier à la racine pooliot-client_config.txt
- écrire:

```
ADDRESS=https://preprod.pooliot.net:9315
TOKEN=
```
Pour obtenir le token, se rendre sur preprod.pooliot.net, puis le rajouter dans le fichier

## Optionnellement

### Pour ajouter le wifi

- créer le fichier `wpa_supplicant.conf`
- écrire

```
country=FR
ctrl_interface=DIR=/var/run/wpa_supplicant GROUP=netdev
update_config=1

network={
    ssid="Terrier"
    psk="c3ntr3dum0nde"
}
```

- Ejecter la carte SD

## Lancement rasp

- insérer la carte SD
- connecter écran
- connecter alimentation







# Keypad Frient (KEPZB-110) for Alarmo (FR/EN)

## Description

### EN:
This project provides a Home Assistant automation blueprint for managing multiple PIN codes using the Frient Keypad (KEPZB-110). It allows arming and disarming your alarm system (Alarmo or other compatible panels) while synchronizing the status between your Frient Keypad and a central alarm system.

### FR :
Ce projet propose un blueprint d'automatisation pour Home Assistant, permettant de gérer plusieurs codes PIN avec le Keypad Frient (KEPZB-110). Il permet d'armer et de désarmer votre système d'alarme (Alarmo ou autres panneaux compatibles), tout en synchronisant l'état entre votre Keypad Frient et un système d'alarme central.

## Features / Fonctionnalités

### EN:
- Manage multiple PIN codes for arming/disarming the alarm system.
- Synchronize alarm states between Frient Keypad and Alarmo (or another alarm panel).
- Support for RFID badges.
- Option to use PIN codes for arming the system.
- Multi-language support (English, French).

### FR :
- Gérer plusieurs codes PIN pour armer/désarmer le système d'alarme.
- Synchroniser les états d'alarme entre le Keypad Frient et Alarmo (ou un autre panneau d'alarme).
- Prise en charge des badges RFID.
- Option d'utilisation des codes PIN pour armer le système.
- Support multilingue (Anglais, Français).

## Installation

### EN:
1. Download and import the blueprint into your Home Assistant instance by clicking the button below.
2. Configure the Frient Keypad device with ZHA or Zigbee integration.
3. Link the blueprint with your alarm panel (Alarmo or any compatible panel).
4. Define valid PIN codes and RFID tags in the blueprint.
5. Enjoy automatic syncing and control of your alarm system with the Frient Keypad.

[![Import Blueprint](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https://raw.githubusercontent.com/Darktoinon/frient_keypad_control/refs/heads/main/frient_keypad_control.yaml)

### FR :
1. Téléchargez et importez le blueprint dans votre instance Home Assistant en cliquant sur le bouton ci-dessous.
2. Configurez le dispositif Keypad Frient avec l'intégration ZHA ou Zigbee.
3. Liez le blueprint avec votre panneau d'alarme (Alarmo ou tout autre panneau compatible).
4. Définissez les codes PIN valides et les badges RFID dans le blueprint.
5. Profitez de la synchronisation automatique et du contrôle de votre système d'alarme avec le Keypad Frient.

[![Importer Blueprint](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https://raw.githubusercontent.com/Darktoinon/frient_keypad_control/refs/heads/main/frient_keypad_control.yaml)

## Usage / Utilisation

### EN:
- **PIN Codes**: You can set multiple valid PIN codes in the blueprint. When entered on the Frient Keypad, the alarm system will arm or disarm depending on the mode selected.
- **RFID Tags**: Add RFID tags to quickly arm or disarm your alarm system without needing to enter a PIN code.
- **Customization**: Adjust the configuration to suit your needs (e.g., using a PIN for arming or syncing with a mirrored alarm panel).

### FR :
- **Codes PIN** : Vous pouvez définir plusieurs codes PIN valides dans le blueprint. Lorsqu'ils sont saisis sur le Keypad Frient, le système d'alarme s'armera ou se désarmera en fonction du mode sélectionné.
- **Badges RFID** : Ajoutez des badges RFID pour armer ou désarmer rapidement votre système d'alarme sans avoir besoin de saisir un code PIN.
- **Personnalisation** : Ajustez la configuration selon vos besoins (ex : utilisation d'un code PIN pour l'armement ou synchronisation avec un panneau d'alarme miroré).

## Contributions

### EN:
Contributions are welcome! Feel free to open issues or submit pull requests to improve functionality or add more language support.

### FR :
Les contributions sont les bienvenues ! N'hésitez pas à ouvrir des issues ou à soumettre des pull requests pour améliorer la fonctionnalité ou ajouter d'autres langues.

## License / Licence

GNU V3 License

## GitHub Repository

[GitHub - Darktoinon](https://github.com/Darktoinon/)

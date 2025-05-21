# Interface-d-enregistrement

C'est une interface simple créée avec Python qui permet d'enregistrer un périphérique audio connecté sur votre ordinateur.

## Fonctionnalités

- Enregistrement audio depuis un micro ou autre périphérique
- Sauvegarde des fichiers audio sur votre ordinateur
- Interface graphique simple

## Prérequis

- Python 3.8 ou plus récent
- [pip](https://pip.pypa.io/en/stable/)

### Dépendances Python

Installez les dépendances nécessaires avec :

```bash
pip install -r requirements.txt
```

Si vous avez une erreur avec `pyaudio`, installez d'abord la bibliothèque système :

```bash
sudo apt-get install portaudio19-dev
```

## Utilisation

1. Clonez le dépôt :

   ```bash
   git clone https://github.com/tonpseudo/Interface-d-enregistrement.git
   cd Interface-d-enregistrement
   ```

2. Installez les dépendances (voir ci-dessus).

3. Lancez le programme :

   ```bash
   python main.py
   ```

## Aide

Si vous avez des problèmes d'installation ou d'utilisation, ouvrez une "issue" sur GitHub ou contactez-moi.

---

**N'hésitez pas à adapter ce texte selon les spécificités de ton projet (nom du fichier principal, options, etc.) !**

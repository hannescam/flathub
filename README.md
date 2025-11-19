# Unofficial [FlatCAM Evo](https://bitbucket.org/marius_stanciu/flatcam_beta.git) Flatpak

Currently it uses the Beta_8.995 branch

## Known issues:

- Settings can't be saved - needs to be fixed upstream
- Sometimes portal saving action produces a weird filename
- Automatic dark/light mode switching broken doe to not having GTK in the Flatpak

## Development

### To regenerate sources
``` bash
python -m flatpak_pip_generator --runtime="org.kde.Sdk//6.10" -r python3-dependencies/requirements.txt --checker-data -o python3-dependencies/requirements
```


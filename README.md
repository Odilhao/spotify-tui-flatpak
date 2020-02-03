# spotify-tui-flatpak


## Building the application

Run the following:

```
cd src
flatpak-builder build-dir com.spotify-tui.spotify-tui.yaml --force-clean
```

## Running the application

Run the following:

```
flatpak-builder --run build-dir com.spotify-tui.spotify-tui.yaml spt
```

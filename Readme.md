## Installieren
```
git clone https://github.com/thorstenkloehn/ahrensburg.git
cd ahrensburg.city
```
## Veröffentlichen

```
dotnet publish -c Release -o ./publish
```
```
rsync -avz --exclude 'App_Data' ./publish/ user@zielserver:/pfad/zum/zielverzeichnis/
```
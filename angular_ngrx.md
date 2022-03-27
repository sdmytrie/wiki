# HOWTO

## Initial Setup

* Json server
```
npm install json-server
```
Create ````json.db```` in the root folder.

* Launch Angular server and json-server, change **package.json** :
``` "start": "concurrently \"ng server\" \"json-server --watch db.json\" " ```

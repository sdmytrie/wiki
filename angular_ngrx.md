# HOWTO

## Initial Setup

*   Json server

<!---->

    npm install json-server

Create `json.db` in the root folder.

*   Install concurently

<!---->
    npm install concurrently

*   Launch Angular server and json-server, change **package.json** :

<!---->
    "start": "concurrently "ng server" "json-server --watch db.json" "\`

*

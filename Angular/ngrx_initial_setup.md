:ngrx:angular:json-server:concurrently:

# NGRX Initial Setup

*   [Angular Developper](https://github.com/angulardeveloper-io/ngrx-store-app)

## Initial Setup

*   Json server

<!---->

    npm install json-server

*   Create `json.db` in the root folder.
*   Install concurently

<!---->

    npm install concurrently

*   Launch Angular server and json-server, change **package.json** :

<!---->

    "start": "concurrently "ng server" "json-server --watch db.json" "\`

*   Create mdoules and compoents

<!---->

```
ng g c component ...
ng g m module ...

```

*   configure routes
* Create UX
*   Install all packages

<!---->

    npm install @ngrx/store @ngrx/effects @ngrx/entity @ngrx/store-devtools @ngrx/router-store

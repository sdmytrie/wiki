:ngrx:angular:json-server:concurrently:

# NGRX Initial Setup

* [Angular Developper](https://www.youtube.com/redirect?event=video_description&redir_token=QUFFLUhqbTlFUXYxLWJ3SEhkV2NUd2ptNXp1SFpOQ3VoUXxBQ3Jtc0trb2FreUY3aDhMaGItZXpRZVd3NWF1eHlXSG5sM1hrcmQwNUk5c3NjNTRQRDN1T3ZOUFoyelltaG5ab1VjXzAxUUZOV3h1UlFDalF0ejVFX2dQdjlRZFlTR1dIVkFkYjRrRkFxbWhPMExFc21MR3pFdw&q=https%3A%2F%2Fgithub.com%2Fangulardeveloper-io%2Fngrx-store-app)

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
*

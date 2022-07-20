# javaScriptADL
Todo mi contenido del módulo de JavaScript del diplomado Desarrollo FullStack JS de Desafío Latam.

Intenté subir todas las carpetas, pero me arrojó algunos mensajes de error, al ejecutar los siguientes comandos (la primera línea es el comando que intenté ejecutar:

    $ git add .
    warning: adding embedded git repository: Desafio 1
    hint: You've added another git repository inside your current repository.
    hint: Clones of the outer repository will not contain the contents of
    hint: the embedded repository and will not know how to obtain it.
    hint: If you meant to add a submodule, use:
    hint:
    hint:   git submodule add <url> Desafio 1
    hint:
    hint: If you added this path by mistake, you can remove it from the
    hint: index with:
    hint:
    hint:   git rm --cached Desafio 1
    hint:
    hint: See "git help submodule" for more information.
    warning: adding embedded git repository: Desafio 2

    $ git commit -m "Primer commit, todas las carpetas de JS"
    [master (root-commit) d806379] Primer commit, todas las carpetas de JS
     2 files changed, 2 insertions(+)
     create mode 160000 Desafio 1
     create mode 160000 Desafio 2

    $ git push -u origin master
    Enumerating objects: 2, done.
    Counting objects: 100% (2/2), done.
    Delta compression using up to 12 threads
    Compressing objects: 100% (2/2), done.
    Writing objects: 100% (2/2), 246 bytes | 246.00 KiB/s, done.
    Total 2 (delta 0), reused 0 (delta 0), pack-reused 0
    To https://github.com/vaalfer/javaScriptADL.git
     * [new branch]      master -> master
    branch 'master' set up to track 'origin/master'.

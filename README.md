Ce repository est un backup de mai 2020 du site web [pierreaudibert.fr](http://pierreaudibert.fr/), un de mes profs de fac Paris 8 aujourd'hui disparu.

Je garde donc une trace de ses travaux et publications sur ce repository public et mentionne que toutes les informations contenues dans cet espace est le fruit du travail de Pierre Audibert.

Vous pouvez visualiser le site sous Docker :

```
docker run --name pierreaudibert -v $(pwd):/usr/share/nginx/html:ro -d -p 8080:80 nginx
```

Test 16.
# Links

Markdown utilie deux types de liens: en ligne et en référence.

Dans les deux styles, le lien teste es delimité par [crochet].

Pour creer un lien en ligne, il faut utiliser les parenthèses apres le liens texte, imédiatemant après le crochet fermant. Entre les parenthèses, placer URL sur laquelle vous souhaitez pointer, vous pouver placer un tire entre guillemets. par exemple:
```markdown

[Je suis un lien en ligne](https://www.google.com)

[Je suis un lien en ligne avec un titre](https://www.google.com "Google's Homepage")

[Je suis un liens référençant un style][Arbitrary case-insensitive reference text]

[Je suis la référence d'un fichier dans un répertoire](../blob/master/LICENSE)
```

les liens Reference-style utilisent une deuxieme serie de crochet, entre crochet vous pouvez placer un nom pour identifier le lien:
```markdown

C'est un [exemple][nom] lien de référence
```

vous pouvez utiliser un espace pour séparer les deux ensembles de crochets (facultatif):

```markdown

C'est un [exemple] [nom] lien de référence
```

En une seule ligne vous pouvez definir le nom d'un lien, n'importe ou dans le document:
```markdown
[nom]: http://example.com/  "titre facultatif"
```

**GitHub** et **GitBook** soutient le marquage automatique des liens. Pour le marquage automatique des liens, vous pouvez faire un lien internet, (sans metre du teste),vous pouvez ecrire le lien internet, il sera considé comme un lien internet.


---

Voici un questionnaire concernant des liens markdown.

Selectionner le bon lien :
- [x] `[a link](http://google.fr)`
- [ ] `(a link)[http://google.fr]`

> le lien texte est délimité par des [crochets].

Qelles sont les informationss correctent pour les liens: ```[un lien](http://google.fr "google")```
- [ ] the link is https://google.fr
- [x] the title of the link is "google"
- [ ] it'll show the text "google"
- [x] it'll show the text "a link"

> les liens peuvent comporter trois parties: un texte, un lien internet et un titre.


---


# Tribunaux mixtes avocats

## Source
Ordre des avocats aux juridictions mixtes d’égypte, _[Tableau de l’Ordre: 59me & 60me Année Judiciares 1933-1935](https://digitalcollections.aucegypt.edu/digital/collection/p15795coll11/id/3173/)_ (Alexandrie: Typo. Fratelli Ventura, 1934), which is digitized by the American University in Cairo.

## Procedure
The source lists every lawyer twice: first in numbered sequence (which I take to be a list of seniority) according to status (Avocats près la Cour, Avocats aux Tribunaux, Avocats Stagiaires), then in alphabetical order. The first list gives the date when the lawyer joined the order. The second list gives the lawyer's address.

Names appear twice, and I carefully reconciled the two lists. There may be a few OCR-produced typos, but because the names were OCRed in two versions, there was a built in check. Two fields preserve alternate spellings that appeared in the first (number-ordered) list; in all other cases, the names were spelled identically.

I also reconciled residences and status (court, tribunal, stagiaire), and produced columns that record any variation between the two tables. In these two cases, I assume that variations indicate a change in residence or status between the time of first membership (in the first table) and current status (in the second table). I was surprised that there was not more movement, however. Also, presumably most lawyers were stagiaires when they first joined, but that status was not given in the first list. All this to say, it's not certain what these variations mean. There are not many of them.

Stagiaires are (in most cases) listed not with a street address but with the name of their patron. The original version of the patron's name is given, and I've also reconciled these names with the patron's order number. There are a few ambiguous cases.

I did this work in January 2022.

## Data dictionary
1. **name**: full series of names, in sequence in which it appears in original document
2. **(surname)**: what I take to be the surname, usually the first name given
3. **(given-name)**: what I take to be the given name, usually the second name given
4. **(other-names)**: the remnant not assigned to previous two columns
6. **name-first-list**: 57 instances of variance between first and second list orthography
7.  **description**: titles given in addition to name: (Mlle) and (Mme), as well as offices within the Order
9. **residence**: Alexandrie, Caire, Mansourah, Port-Said
10. **(changed-residence-from)** 17 instances of variance between first and second lists
11. **date**: presumably of membership in the Order
12. **address-concat**: I produced this from a concatenation of the next two fields, which I cleaned
13. **street-number**: split from address
14. **street**: split from address
15. **(street-reconcile)**: partial standardization of street names, mostly by substituting "Rue" for "Chareh" and the like. I'm using this for disambiguation.
16. **c/o**: name of mentors of stagiaires. Mentors in partnership listed as "Mes."
17. **(patron-no)**: mentor's number in this Order list. When it's not clear, I listed more than one possibility.
18. **(parton-partner-no)**: second mentor's number, in cases of partnership. When it's not clear, I listed more than one possibility.
19. **(stagiaire-no)**: number(s) of stagiaire(s). I produced this column from the two preceding columns, and have noted ambiguous cases.
20. **Status**: from second list
21. **Type-a**: section of first list
22. **(type-change)**: 15 instances of variance between first and second lists
23. **No**: number in this document's ordered sequence
24. **telephone**: telephone number listed in second list

## To do
- [x] I'd like to add a column showing the stagiaires each lawyer took on. (2022-01-23)
- [ ] I'd also like to indicate relationships (i.e., those who work out of the same office).
- [x] I need to work on names. I've split surnames and given names, but there are problems of name sequence. This is especially true for Arabic names and for middle initials. (2022-01-23)
- [ ] I think there are some unescaped characters, for some reason. I haven't been able to convert the text successfully. I see this in OpenRefine, when trying to combine faceted records. Probably not a big deal, but I wish I had it sorted out.

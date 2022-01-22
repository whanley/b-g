# Tribunaux mixtes avocats

## Source
Ordre des avocats aux juridictions mixtes d’égypte, [Tableau de l’Ordre: 59me & 60me Année Judiciares 1933-1935](https://digitalcollections.aucegypt.edu/digital/collection/p15795coll11/id/3173/) (Alexandrie: Typo. Fratelli Ventura, 1934), which is digitized by the American University in Cairo.

## Procedure
The source lists every lawyer twice: first in numbered sequence (which I take to be a list of seniority) according to status (Avocats près la Cour, Avocats aux Tribunaux, Avocats Stagiaires), then in alphabetical order. The first list gives the date when the lawyer joined the order. The second list gives the lawyer's address.

Names appear twice, and I carefully reconciled the two lists. There may be a few OCR-produced typos, but because the names were OCRed in two versions, there was a built in check. Two fields preserve alternate spellings that appeared in the first (number-ordered) list; in all other cases, the names were spelled identically.

I also reconciled residences and status (court, tribunal, stagiaire), and produced columns that record any variation between the two tables. In these two cases, I assume that variations indicate a change in residence or status between the time of first membership (in the first table) and current status (in the second table). I was surprised that there was not more movement, however. Also, presumably most lawyers were stagiaires when they first joined, but that status was not given in the first list. All this to say, it's not certain what these variations mean. There are not many of them.

Stagiaires are (in most cases) listed not with a street address but with the name of their patron. The original version of the patron's name is given, and I've also reconciled these names with the patron's order number. There are a few ambiguous cases.

I did this work in January 2022.

## Data dictionary
1. **surname**: what I take to be the surname, i.e. the first name given in each list. There are problems, though.
2. **names**: mostly given names; the rest of the names listed
3. **surname-first-list**: 28 instances of variance between first and second list orthography
4. **names-first-list**: 31 instances of variance between first and second list orthography
5. **description**: titles given in addition to name: (Mlle) and (Mme), as well as offices within the Order
6. **residence**: Alexandrie, Caire, Mansourah, Port-Said
7. **(changed-residence-from)** 17 instances of variance between first and second lists
8. **date**: presumably of membership in the Order
9. **address-concat**: I produced this from a concatenation of the next two fields, which I cleaned
10. **street-number**: split from address
11. **street**: split from address
12. **(street-reconcile)**: partial standardization of street names, mostly by substituting "Rue" for "Chareh" and the like. I'm using this for disambiguation.
13. **c/o**: name of mentors of stagiaires. Mentors in partnership listed as "Mes."
14. **(patron-no)**: mentor's number in this Order list. When it's not clear, I listed more than one possibility.
15. **(parton-partner-no)**: second mentor's number, in cases of partnership. When it's not clear, I listed more than one possibility.
16. **Status**: from second list
17. **Type-a**: section of first list
18. **(type-change)**: 15 instances of variance between first and second lists
19. **No**: number in this document's ordered sequence
20. **telephone**: telephone number listed in second list

## To do
- I'd like to add a column showing the stagiaires each lawyer took on. I'd also like to indicate relationships (i.e., those who work out of the same office).
- I need to work on names. I've split surnames and given names, but there are problems of name sequence. This is especially true for Arabic names and for middle initials. 
- I think there are some unescaped characters, for some reason. I haven't been able to convert the text successfully. I see this in OpenRefine, when trying to combine faceted records. Probably not a big deal, but I wish I had it sorted out.
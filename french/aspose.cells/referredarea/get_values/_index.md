---
title: méthode get_values
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 30
url: /fr/aspose.cells/referredarea/get_values/
is_root: false
---
##  get_values(self) {#}
Obtient les valeurs des cellules dans cette zone.


###  Retour

Si cette zone n'est pas valide, "#REF!" sera restitué ;
Si cette zone est une seule cellule, renvoyez l'objet valeur de cellule ;
Sinon, renvoyez un tableau 2D pour toutes les valeurs de cette zone.


```python

def get_values(self):
    ...
```




##  get_values(self, calculate_formulas) {#bool}
Obtient les valeurs des cellules dans cette zone.


###  Retour

Si cette zone n'est pas valide, "#REF!" sera restitué ;
Si cette zone est une seule cellule, renvoyez l'objet valeur de cellule ;
Sinon, renvoyez un tableau 2D pour toutes les valeurs de cette zone.


```python

def get_values(self, calculate_formulas):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| calculate_formulas | bool | Dans cette gamme, s'il y a des formules qui n'ont pas été calculées,<br/> cet indicateur indique si ces formules doivent être calculées de manière récursive|



###  Voir également
* module [`aspose.cells`](../../)
* classe [`ReferredArea`](/cells/python-net/fr/aspose.cells/referredarea)

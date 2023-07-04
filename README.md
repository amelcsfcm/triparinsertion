Le tri par insertion considère chaque élément du tableau et l'insère à la bonne place parmi les éléments déjà triés. Ainsi, au moment où on considère un élément, les éléments qui le précèdent sont déjà triés, tandis que les éléments qui le suivent ne sont pas encore triés.

Pour trouver la place où insérer un élément parmi les précédents, il faut le comparer à ces derniers, et les décaler afin de libérer une place où effectuer l'insertion. Le décalage occupe la place laissée libre par l'élément considéré. En pratique, ces deux actions s'effectuent en une passe, qui consiste à faire « remonter » l'élément au fur et à mesure jusqu'à rencontrer un élément plus petit.

Le tri par insertion est un tri stable (conservant l'ordre d'apparition des éléments égaux) et un tri en place (il n'utilise pas de tableau auxiliaire).

L'algorithme a la particularité d'être online, c'est-à-dire qu'il peut recevoir la liste à trier élément par élément sans perdre en efficacité.# triparinsertion

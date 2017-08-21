

# Cycle de vie des composants et fonction composants react :
 
 

### componentWillMount() :
 est exécutée avant le rendu, à la fois côté serveur et client.

### componentDidMount() :
est exécutée après le première rendu uniquement surle côté client.
Ceci est le cas des requêtes AJAX et DOM ou des mises à jour de l'Etat devraient se produire.
Cette méthode est également utilisée pour l' intégration avec d' autres frameworks JavaScript et toutes les fonctions avec l' exécution différée comme setTimeout ou setInterval.
Nous l'utilisons pour mettre à jour l'état afin que nous puissions déclencher les autres méthodes de cycle de vie.

### componentWillReceiveProps() :
est invoquée dès que les accessoires sont mis à jour avant qu'un autre rendu est appelé. Nous déclenché à partir de setNewNumber quand nous mis à jour l'état.

### shouldComponentUpdate() :
doit retourner la valeur true ou false. Cela permettra de déterminer si le composant sera mis à jour ou non. Ceci est la valeur true par défaut. Si vous êtes sûr que le composant n'a pas besoin de rendre après l' état ​​ou les accessoires sont mis à jour, vous pouvez retourner la valeur false.

### componentWillUpdate() :
est appelé juste avant le rendu.

### componentDidUpdate() :
est appelé juste après le rendu.

### componentWillUnmount() :
est appelé après que le composant est démonté à partir du Royaume. Nous Démonter notre composant main.js.









#### Source : http://www.w3ii.com/fr/reactjs/reactjs_component_life_cycle.html

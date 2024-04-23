# Exposés 23 24

## GraphQL (par Tom Balieu)

Alternative au APIs REST et approche moderne de déliverance des données.

### Kesako ?

GraphQL est un langage de requête pour votre API et un environnement d'exécution de requêtes côté serveur pour exécuter ces requêtes en utilisant les données existantes. GraphQL décrit les données de l'API et fourni un moyen d'accès à ces données. Il suffit de piocher ce dont vous avez besoin.

### Pourquoi GraphQL ?

- **Demander ce dont vous avez besoin** : GraphQL permet aux clients de demander des données exactement comme ils en ont besoin. GraphQL est une alternative aux API REST.

- **Un seul point d'entrée** : GraphQL fournit un seul point d'entrée pour exécuter des requêtes. Cela signifie que vous n'avez pas besoin de gérer plusieurs points d'entrée pour différentes versions de votre API.

- **Documentation automatique** : GraphQL fournit une documentation automatique pour votre API. Cela signifie que vous n'avez pas besoin de maintenir une documentation séparée pour votre API.

- **Évolution de l'API** : GraphQL permet d'évoluer l'API sans casser les clients existants. Cela signifie que vous pouvez ajouter de nouveaux champs à votre API sans casser les clients existants.

- **Outils de développement** : GraphQL fournit des outils de développement puissants pour les développeurs. Cela signifie que vous pouvez, par exemple, utiliser des outils tels que GraphiQL pour tester vos requêtes GraphQL.

## Pourquoi ne pas l'utiliser ?

- **Cache** : GraphQL a du mal à cacher ses données car contrairement aux API REST, les méthodes de caching ne sont pas définis par les CDNs, Proxies, Serveurs Web, et navigateurs.
- **Coût de l'infrastructure** : GraphQL nécessite plus de ressources pour exécuter des requêtes que les API REST.
- **Client Integration** Contrairement aux API REST, GraphQL nécessite un client spécialisé pour exécuter des requêtes. Cela signifie que vous devez utiliser un client GraphQL pour exécuter des requêtes GraphQL là où en REST, on utilise des outils simples comme cURL, intégrés dans la plupart des cas par défaut.

### Comment ça marche ?

GraphQL est composé de 5 parties principales :

1. Queries (requêtes) : Les requêtes GraphQL sont utilisées pour demander des données spécifiques au serveur. Elles permettent aux clients de spécifier exactement quelles données ils ont besoin, et le serveur renvoie uniquement ces données.

2. Mutations (mutations) : Les mutations sont utilisées pour modifier les données du serveur. Contrairement aux requêtes, qui sont utilisées pour la lecture de données, les mutations permettent d'effectuer des opérations telles que la création, la mise à jour ou la suppression de données.

3. Types (types) : GraphQL définit un système de types pour décrire la structure des données disponibles. Les types sont utilisés pour spécifier quels champs peuvent être demandés sur un objet et quels types de données ils contiennent.

4. Schemas (schémas) : Un schéma GraphQL est une description de tous les types de données disponibles dans l'API, ainsi que des relations entre ces types. Il définit quels types de requêtes et de mutations peuvent être exécutés.

5. Resolvers (résolveurs) : Les résolveurs sont des fonctions qui définissent comment les données doivent être récupérées ou modifiées pour chaque champ d'un type dans le schéma. Chaque champ d'un type peut avoir son propre résolveur, ce qui permet une grande flexibilité dans la façon dont les données sont obtenues ou manipulées.

![Démonstration du fonctionnement - GraphQL](https://raw.githubusercontent.com/graphql/graphiql/main/packages/codemirror-graphql/resources/example.gif)

### Exemple

Voici un exemple de requête GraphQL :

```graphql
query {
  user(id: 1) {
    id
    name
    email
  }
}
```

### Experimenter

Dirigez-vous vers l'[API GraphQL d'Atlassian](https://hello.atlassian.net/gateway/api/graphql)

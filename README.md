# Pour installer Bootstrap via NPM

```
npm i bootstrap
npm i jquery
npm i popper.js
```

Pour que npm installe automatique les dépendences liées (peerDependencies)
https://www.npmjs.com/package/install-peers


# Charger boostrap sur notre application

Les éléments à charger
- CSS bootstrap
- JS bootstrap
- JS jquery
- JS Popper


```
...
<head>
    ...
    <link rel="stylesheet" href="node_modules/bootstrap/dist/css/bootstrap.min.css">
</head>
...
<body>
    ...
    <script src="node_modules/jquery/dist/jquery.min.js"></script>
    <script src="node_modules/popper.js/dist/popper.js"></script>
    <script src="node_modules/bootstrap/dist/js/bootstrap.min.js"></script>
</body>
```
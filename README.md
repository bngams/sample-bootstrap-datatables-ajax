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

# Utiliser datatables.net sur notre application

Installation

```
npm install datatables.net-bs4
npm install datatables.net
```

Scripts et fichiers styles à inclure dans notre html

```
...
<head>
    ...
    <link rel="stylesheet" href="node_modules/datatables.net-bs4/css/dataTables.bootstrap4.min.css">
</head>
...
<body>
    ...
    <script src="node_modules/datatables.net/js/jquery.dataTables.min.js"></script>
    <script src="node_modules/datatables.net-bs4/js/dataTables.bootstrap4.min.js"></script>
</body>
```
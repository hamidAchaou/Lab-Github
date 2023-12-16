
##  les commandes  utiliser  pour faire le travail 

1. Vérification de la Branche `master`

```shell
    git branch
```
```shell
    git checkout master
```
2. Création des Branches `feature_1`, `feature_2` 

```bash
    git checkout -b feature_1 master  
```
```shell
    git checkout master  
```
```shell
    git checkout -b feature_2 master  
```

3. Fusion des Branches de Travail dans `master`

```bash
    git checkout master  
```
```shell
    git merge feature_1 
```
```shell
    git merge feature_2   
```

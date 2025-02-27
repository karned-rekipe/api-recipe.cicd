# Helm de déploiement d'API Recipe

**Déploiement**
```sh
 helm install api-recipe ./api-recipe -f api-recipe/values_sample.yaml
```

**Suppression**
```sh
helm uninstall api-recipe -n <namespace>
```
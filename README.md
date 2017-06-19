### Update DC
```sh
oc new-app https://github.com/i63/store-frontend --name=store --strategy=source
oc env dc store-frontend inventory_svc=inventory products_svc=products
```

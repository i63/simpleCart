### Update DC
```sh
oc new-app https://github.com/i63/store-frontend --name=store --strategy=source
oc env dc store inventory_svc=http://inventory:8000 products_svc=http://products:8080
```

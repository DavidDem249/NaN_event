# NaN_event

UN EXEMPLE DE FONCTION D'UN SYSTEME D'EVENEMENT

##users
```
id int(11) NOT NULL PRIMARY KEY ,
email varchar(70) NOT NULL ,
password,
username,
photo
```
events(id,titre,description,date_heure,lien_gmap,lieu,prix,ville_id,commune,photo,admin_id)
ville(id,nom)
images(id,path,event_id)


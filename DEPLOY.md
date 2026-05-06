# Guide de d é ploiement -- TerrangaFood

## 1. MongoDB Atlas
- Cluster : terrangafood -[ code-chill ] ( M0 Free , AWS Paris )
- Utilisateur : terrangafood - admin
- Accès réseau : 0.0.0.0/0
- Base : terrangafood
- Seed : exécuté avec 5 restaurants + 27 plats


## 2. Render ( API Express )
- Service : terrangafood - api -[ code-chill ]
- URL : https://terrangafood-code-chill.onrender.com/
- Root Directory : api
- Runtime : Node
- Instance : Free
- Variables : MONGODB_URI ( Atlas ) , PORT (3001)
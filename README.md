# Load Balancer

Implémenter un serveur de load balancing (**HTTP** + **Websocket**). Le serveur doit accepter une liste de ports en variable d'environement ou argument de ligne de commande:

```
$ ./load-balancer.js 5001,5002,5003

ou

$ PORTS=5001,5002,5003 ./load-balancer.js
```

Module à utiliser: `ws`, `http`, ou `net`

### Bonus

1. Ecrire plusieurs strategies de balancing: Roundrobin, random
2. Ecrire des tests d'integrations sur le serveur

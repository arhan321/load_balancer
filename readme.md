# konfig nginx load balancer berbasis container
```
docker nginx
```
- jika biasanya load balancer menggunakan nginx bawaan, 
maka ini saya melakukan experiment melakukan load balancer
berbasis container, jadi bikin container :
```
nginx1 nginx2 nginx3 dan (container untuk controll pusat nya)
```
# struktur-folder
```plaintext
|-- src
|   |-- index.html
|-- docker-compose.yml
|-- dockerfile (pull depedencies)
|-- nginx-lb.conf (control balancer)
|-- nginx.conf (parameter config nginx)
```

# ini adalah ilmu devops
```
HAPPY CODINGG!!!
```

# open source
```
freee useee !!!
```
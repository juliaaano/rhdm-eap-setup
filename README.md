# Red Hat Decision Server

As known as the KIE Server.

## Quick Start

 Install JBoss EAP and RHDM Server:
 ```
 ./install.sh
 ```

Apply patches:
```
./patch.sh
```

 Add 'kieserver' user:
 ```
 ./users.sh
 ```

Review the setup.properties file and run:
```
./setup.sh
```

Start the server:
```
./run.sh
```

## More options

 Install offline, without downloading files:
 ```
 ./install.sh offline
 ```

Start the server with port offset (to avoid port conflict):
```
./run.sh -Djboss.socket.binding.port-offset=100
```

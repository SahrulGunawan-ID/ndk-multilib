# ndk-multilib
 NDK-MULTILIB 

FOR TERMUX INSTALLER
````
apt update && apt upgrade -y
````
````
apt install x11-repo -y
````
````
apt install root-repo -y
````
````
apt install clang -y
````

# add static link via ndk
````
apt install ndk-multilib-native-stubs -y
````
````
apt install ndk-multilib-native-static -y
````
````
apt install ndk-sysroot -y
````
````
apt install ndk-multilib -y
````
````
apt install build-essential make cmake -y
````

# Create Example C
*hello.c*
````c
#include <stdio.h>

int main() {
    printf("Hello, world!\n");
    return 0;
}
````
# Create Not Static 
````
gcc -o hello hello.c
````
# Create Static No Link Library
````
gcc -static -o hello hello.c
````

# Screenshot
![Deskripsi Gambar](https://raw.githubusercontent.com/SahrulGunawan-ID/ndk-multilib/refs/heads/main/Screenshot_2025-04-25-21-12-02-80.png)

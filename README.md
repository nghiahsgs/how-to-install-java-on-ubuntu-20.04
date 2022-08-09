# how-to-install-java-on-ubuntu-20.04
how to install java on ubuntu 20.04

```
sudo apt update
```

install java
```
sudo apt install default-jre
```

```
java -version
```


install javac
```
sudo apt install default-jdk
```

```
javac -version
```

run the first program in java language
```
vi hello.java
```

```
// Your First Program
class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello, World!"); 
    }
}
```

```
javac hello.java
java HelloWorld
```

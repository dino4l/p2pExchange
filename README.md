# p2pExchange
Application for exchanging files between arbitrary users of a computer network through the establishment of a peer-to-peer connection 


## Example:

1. Starting 6 terminals with 1 file owner and 5 peers:

```
cd Peer1_Owner
javac FileOwner.java
```

```
cd Peer2
javac Peer.java
```

```
cd Peer3
javac Peer2.java
```

```
cd Peer4
javac Peer.java
```

```
cd Peer5
javac Peer5.java
```

```
cd Peer6
javac Peer6.java
```

![image](https://user-images.githubusercontent.com/81106878/132889420-34a53867-d958-4f93-a810-82b561f7aeba.png)


2. Сonnecting the peer to the file owner

![image](https://user-images.githubusercontent.com/81106878/132889647-c9555dbb-c25b-42c2-8544-a18f224ef9ee.png)


3. Transferring file blocks from the file owner 

![image](https://user-images.githubusercontent.com/81106878/132889823-37223c79-52a0-4787-8a4e-16a243712646.png)

4. Receiving file blocks by a peer from a peer 

![image](https://user-images.githubusercontent.com/81106878/132889979-ef544673-6cd7-4779-b18b-6659dbf0a3ff.png)


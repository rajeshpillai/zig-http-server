# Zig Server
A simple Zig server


# Usage
To run the app  (The server runs on default port 9000).  To change the port pass the numeric port number after the dir argument

```
zig run src/self-serve -- public

# Run on port 3001
zig run src/self-serve -- public 3001
```


# To build the app
```
zig build

```


# Run the build (serve from public folder)
```
./zig-out/bin/self-serve public
```
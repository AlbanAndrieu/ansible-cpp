# ansible-cpp

A role for installing cpp.


## Actions

- Ensures that cpp is installed (using `apt`)


## Usage:
```
  - name: Install cpp
    hosts: cpp
    user: root
  #  connection: local
    
    roles:
      - cpp      
```

## License

MIT

To initialize the EVerest workspace you can source to *[init.sh](./init.sh)* file:

```bash
chmod u+x init.sh
. init.sh
```

The working directory will be changed to everest-core/build. Here you can use cmake and make to build the project:

```bash
cmake .. && make install
```
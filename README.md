# fwlib & swig

```bash
git submodule update --init --recursive
# depending on architecture
ln -s extern/fwlib/libfwlib32-linux-x64.so.1.0.5 libfwlib32.so
./build.sh
LD_LIBRARY_PATH=. python3 test.py
```

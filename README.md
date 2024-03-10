# Decrypte-Marshal
Decrypte Marshal Method for python3 + first time in GitHub 

### How it works?

This tool use disassembling for convert marshal bytes to pyc
then you can decompile pyc to py with Famous PycDc tool.

### How can i run it? ([Watch Video](https://raw.githubusercontent.com/aDarkDev/Decrypte-Marshal/main/4_5942911484009912592.mp4))

first of all download and install PycDc ( PYC Decrypte )

```bash
git clone https://github.com/zrax/pycdc
sudo apt install cmake
cd pycdc&& cmake .
make
```

then put byteString.txt in your project
import dis assembly library like this:
```python
import dis
import marshal
```
run project to get aDarkDev.pyc

decompile pyc with this command

```bash
./pycdc aDarkDev.pyc
```

#Support Us!
Tangs

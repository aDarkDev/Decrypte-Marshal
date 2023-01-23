# Decrypte-Marshal
Decrypte Marshal Method for python3 + first time in GitHub 

### How it works?

This tool use disassembling for convert marshal bytes to pyc
then you can decompile pyc to py with Famous PycDc tool.

### How can i run it? ([Watch Video]())

first of all download and install PycDc ( PYC Decrypte )

```bash
git clone https://github.com/zrax/pycdc
cd pycdc&& cmake .
make
```

then put byteString.txt in your project
import dis assembly library like this:
```python
import dis
import marshal
```
run project to get ConfusedCharacter.pyc

decompile pyc with this command

```bash
./pycdc ConfusedCharacter.pyc
```

#Support Us!

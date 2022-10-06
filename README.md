# ctc-playground
ctc (Check the Chain) playground

# Prerequisits
python3
pip

# Setup
python3 -m venv venv
source venv/bin/activate
pip install checkthechain
ctc setup

# Favorite commands

```console
ctc decompile [ADDRESS]
ctc call all [ADDRESS] # Requries verified on etherscan
ctc call [ADDRESS] [FUNCTION OR ABI] [ARGS]
```

Useful for standard ABIs
https://www.smartcontracttoolkit.com/abi

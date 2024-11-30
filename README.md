# Ultrakill on linux guide (With mods)
How to run Modded ULTRAKILL on linux

## Requirements:
- Latest release of wine
- Latest UNIX release of [r2modman](https://github.com/ebkr/r2modmanPlus)
- Know where your ULTRAKILL folder is located

## Guide:
### Wine configuration
1. Open winecfg on terminal of your choice and run winecfg
2. Go to the libraries tab and add winhttp 

### r2modman configuration
1. Open r2modman then select ultrakill with the default profile
2. Add the mods of your choice
3. Go to "Settings > Debugging > Set launch parameters" and copy the Modded parameters

### Launching the modded version
To launch the modded version just run on your terminal:
`wine start /unix [path to the ultrakill executable] [r2modman arguments]`

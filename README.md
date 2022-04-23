# cool-retro-term-equalizer
   
   
equalizer using cool-retro-term, cava &amp; ncmpcpp
   
- cool-retro-term  https://github.com/Swordfish90/cool-retro-term
- cava https://github.com/karlstav/cava
- ncmpcpp  https://github.com/arybczak/ncmpcpp
    
    
Fix for 'module "QMLTermWidget" is not installed':
```sh
#!/bin/bash
exec /home/exitlight/cool-retro-term/cool-retro-term
```
  
   
`# cp cool-retro-term-fix.sh /bin/cool-retro-term`
  
```sh
git clone --recursive https://github.com/Swordfish90/cool-retro-term.git
cd cool-retro-term
qmake && make
sudo make install
```
  
```sh
git clone --recursive https://github.com/arybczak/ncmpcpp.git
cd ncmpcpp
./autogen.sh
./configure
make
sudo make install
```
  
```sh
git clone --recursive https://github.com/karlstav/cava.git
cd cava 
./autogen.sh
./configure
make
sudo make install
```
  

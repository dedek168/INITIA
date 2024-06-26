1. Check Version 
```
   root@Ubuntu-2204 ~ # initiad version
        output: v0.2.21
```
3. How to update
```
   root@Ubuntu-2204 ~ #  cd $HOME
                            rm -rf initia
                            git clone https: //github.com/initia-labs/initia.git
                            cd initia
                            git checkout v0.2.21
                            make build
                            sudo mv build/initiad /usr/local/bin/
```

# Instalação

```bash
sudo apt install -y ccrypt
```

# criptogragar arquivo

```bash
ccrypt -e teste01.md
```

# descriptografar arquivo

```bash
ccrypt -d teste01.md.cpt
```

# criptografa vários arquivos dentro de uma pasta com a mesma senha

```bash
ccrypt -e -r teste_file/

ou

ccrypt -er teste_file/

```

# decriptografar vários arquivos dentro de uma pasta com a mesma senha

```bash
ccrypt -d -r teste_file/

ou

ccrypt -dr teste_file/
```

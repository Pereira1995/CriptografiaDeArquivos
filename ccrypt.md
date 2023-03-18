## Instalação

```bash
sudo apt install -y ccrypt
```

## criptografar arquivo

```bash
ccrypt -e teste01.md
```

## descriptografar arquivo

```bash
ccrypt -d teste01.md.cpt
```

## criptografar vários arquivos dentro de uma pasta com a mesma senha

```bash
ccrypt -e -r teste_file/

ou

ccrypt -er teste_file/

```

## descriptografar vários arquivos dentro de uma pasta com a mesma senha

```bash
ccrypt -d -r teste_file/

ou

ccrypt -dr teste_file/
```

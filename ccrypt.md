## Instalação

```bash
sudo apt install -y ccrypt
```

## criptografar arquivo

```bash
ccrypt -e file.md
```

## descriptografar arquivo

```bash
ccrypt -d file.md.cpt
```

## criptografar vários arquivos dentro de uma pasta com a mesma senha

```bash
ccrypt -e -r folder/

ou

ccrypt -er folder/

```

## descriptografar vários arquivos dentro de uma pasta com a mesma senha

```bash
ccrypt -d -r folder/

ou

ccrypt -dr folder/
```

SITE OFICIAL: <https://ccrypt.sourceforge.net/>

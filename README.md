# DESAFIO: Primeiro projeto no Github

## Desafio:

Você deve criar um novo projeto no seu computador contendo pelo menos um arquivo texto na linguagem da sua preferência (HTML, VisualG, Java, etc.). Fazer modificações no projeto salvando pelo menos três commits nele, e depois salvar esse projeto como um repositório no seu Github.

## Iniciando com Git

Após a instalação no Sistema Operacional verificar se o git foi instalado corretamente

```
git
git -v
git --version
```

## Configuração inicial do Git

```
git config --global user.name "Mateus Manosso Barszcz"
git config --global user.email "matzbar@gmail.com"
git config --list
```

## Criando a hash SSH

```
ssh-keygen -t ed25519 -C "matzbar@gmail.com"
```

## Inicializando um repositório em um diretório existente

Cria um arquivo e README.md e insere um título para o arquivo.

```
echo "# DESAFIO: Primeiro projeto no Github" >> README.md
```

### Criando um esqueleto do repositório Git
```
git init
```

### Iniciando o controle de versão
```
git status
git add .
git status
git commit -m "Primeiro commit"
git status
```

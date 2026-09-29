![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![PyAutoGUI](https://img.shields.io/badge/PyAutoGUI-2C2C2C?style=flat&logo=python&logoColor=white)
![PyInstaller](https://img.shields.io/badge/PyInstaller-FFD43B?style=flat&logo=python&logoColor=black)

# Automações

Coleção de automações desenvolvidas em Python para facilitar e automatizar tarefas simples do dia a dia.

## Tecnologias utilizadas

- **Python** — linguagem utilizada no desenvolvimento das automações.
- **PyAutoGUI** — responsável pela interação automatizada com teclado, mouse e interface gráfica.
- **PyInstaller** — utilizado para transformar os arquivos `.py` em executáveis `.exe`.

## Instalação

### 1. Clone ou baixe o projeto

Baixe este repositório para o seu computador e abra o terminal na pasta do projeto.

### 2. Instale as dependências

Execute:

```bash
pip install -r requirements.txt
```

O arquivo `requirements.txt` contém as bibliotecas necessárias para executar e compilar as automações.

## Executando uma automação

Depois de instalar as dependências, execute o arquivo Python desejado:

```bash
python nome_do_arquivo.py
```

Substitua `nome_do_arquivo.py` pelo nome do arquivo que deseja executar.

## Gerando um executável `.exe`

O **PyInstaller** permite transformar uma automação Python em um executável que pode ser iniciado diretamente no Windows.

### 1. Abra o terminal

Você pode utilizar o **Prompt de Comando** ou o **PowerShell**.

### 2. Navegue até a pasta do projeto

Utilize `cd` para acessar a pasta onde está o arquivo `.py`:

```bash
cd caminho/para/sua/pasta
```

### 3. Gere o executável

Execute:

```bash
pyinstaller --onefile nome_do_arquivo.py
```

Substitua `nome_do_arquivo.py` pelo arquivo que deseja transformar em executável.

### 4. Localize o executável

Após o processo, o PyInstaller criará algumas pastas e arquivos no projeto. O executável estará localizado em:

```text
dist/
└── nome_do_arquivo.exe
```

O arquivo dentro da pasta `dist` pode ser executado diretamente no Windows.

## Estrutura básica

```text
automações/
├── dist/
├── build/
├── nome_do_arquivo.py
├── requirements.txt
└── README.md
```

---

Arquivos presentes:

- `iniciarProgramacao.py` - uma automação que abre o GitHub, GitHub Desktop e Spotify

# Cybermans Anti-Ransomware

## 📁 Arquivos 

### Sistema de Iniciador Principal
- **`launcher.py`** - Iniciador principal que gerencia privilégios de administrador e instala dependências
- **`launcher.bat`** - Arquivo batch wrapper para execução fácil


### Documentação

- **`README_EXECUTAVEL.md`** - Este arquivo de resumo

## 🎯 Como Usar

### Para Usuários Finais (Sem Python Necessário)

1. **Início Rápido:**
   - Clique duas vezes em `launcher.bat`
   - A aplicação solicitará automaticamente privilégios de administrador e instalará dependências

2. **Instalação Completa:**
   - Execute `python setup.py` e escolha opção 2
   - Isso cria atalhos da área de trabalho e instalação adequada do sistema

3. **Executável Independente:**
   - Execute `python setup.py` e escolha opção 3
   - Isso cria um arquivo `.exe` distribuível


## 🛠️ Solução de Problemas

### Problemas Comuns:

1. **"Python não encontrado"**
   - Instale Python 3.8+ de https://python.org
   - Certifique-se de que Python está adicionado ao PATH

2. **"Acesso negado"**
   - Execute como administrador
   - O iniciador deve lidar com isso automaticamente

3. **"Falha ao instalar dependências"**
   - Verifique conexão com internet
   - Tente executar `pip install -r requirements.txt` manualmente

4. **"GUI não inicia"**
   - Verifique se todos os arquivos Python estão presentes
   - Certifique-se de que `GUI_PART_2.py` está no mesmo diretório





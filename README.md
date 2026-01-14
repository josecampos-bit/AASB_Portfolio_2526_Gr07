# AASB_Portfolio_2526_Gr07

## Descrição

Este repositório contém o portfólio da disciplina **AASB**, referente ao ano letivo **2025/2026**, do **Grupo 07**.  
Trata-se de um **package Python** para manipulação e análise de sequências biológicas (DNA, RNA e aminoácidos).  

O código oferece tanto uma abordagem **funcional** como **orientada a objetos** e inclui funcionalidades como:

- Estatísticas e operações sobre sequências biológicas  
- Transcrição de DNA para RNA e tradução para proteínas  
- Identificação de ORFs (*Open Reading Frames*)  
- Alinhamentos de sequências: globais, locais e progressivos  
- Análise filogenética e estudo de relações evolutivas  
- Detecção de motifs usando expressões regulares (*regex*) ou métodos probabilísticos  

O projeto segue boas práticas de **engenharia de software**, incluindo testes unitários, documentação clara, **type hints** e análises de qualidade do código.

---

## Instalação

### Pré-requisitos
- Python 3.x  
- pip  
- Git (opcional)  

### Passos

```bash
# Clonar o repositório
git clone https://github.com/BrandaoGoated/AASB_Portfolio_2526_Gr07.git
cd AASB_Portfolio_2526_Gr07

# Criar e ativar ambiente virtual (recomendado)
python3 -m venv venv
source venv/bin/activate   # Linux/macOS
# venv\Scripts\activate    # Windows

# Instalar dependências
pip install -r requirements.txt

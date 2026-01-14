# AASB Portfolio 2526 – Grupo 07

## Descrição

Este repositório contém o portfólio da disciplina **AASB**, referente ao ano letivo **2025/2026**, do **Grupo 07**.  
O projeto consiste num **package Python** desenvolvido para a manipulação e análise de sequências biológicas, incluindo **DNA, RNA e aminoácidos**.  

O código permite tanto uma abordagem **funcional** como **orientada a objetos**, oferecendo ferramentas para:

- Estatísticas e operações sobre sequências biológicas  
- Transcrição de DNA para RNA e tradução para proteínas  
- Identificação de ORFs (*Open Reading Frames*)  
- Alinhamentos de sequências: globais, locais e progressivos  
- Análise filogenética e estudo de relações evolutivas  
- Detecção de motifs usando expressões regulares (*regex*) ou métodos probabilísticos  

Além disso, o projeto segue boas práticas de **engenharia de software**, incluindo:

- **Testes unitários** para garantir o correto funcionamento  
- **Documentação clara** de funções e módulos  
- **Type hints** para maior segurança e legibilidade do código  
- Medidas de qualidade de software, como análise de complexidade e cobertura de testes  

Este portfólio serve como demonstração das competências adquiridas em programação Python e bioinformática, ao mesmo tempo que reforça boas práticas de desenvolvimento de código.

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

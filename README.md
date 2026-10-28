# Materiais do curso — Ciência de Dados

Repositório de estudos e exercícios realizados durante um curso de Ciência de Dados. O conteúdo está organizado por notebooks, temas e bases de apoio. Este repositório preserva o material de aprendizagem; nem todos os notebooks representam projetos finalizados ou revisados para uso profissional.

## Conteúdo

- `notebooks/`: trilha organizada por módulos, de fundamentos a cloud.
- `Aula_Pandas/`: exercícios de manipulação de dados com Pandas.
- `Machine Learning/`: estudos de regressão e análise exploratória.
- `Scraping/`: estudo de web scraping.
- `CRUD_operations/`: exemplo de operações CRUD com SQLite.
- `data/`: bases usadas pelos notebooks.
- `Álgebra Linear/`: exercícios com NumPy e SymPy.

## Como começar

Recomendado: Python 3.10 ou 3.11 em ambiente virtual. Instale as dependências que forem necessárias para o notebook escolhido; a lista de `requirements.txt` é mínima e alguns notebooks antigos podem precisar de bibliotecas adicionais ou ajustes.

```bash
python -m venv .venv
# Windows: .venv\Scripts\activate
# macOS/Linux: source .venv/bin/activate
pip install -r requirements.txt
pip install matplotlib seaborn scikit-learn statsmodels
jupyter lab
```

Abra um notebook e execute as células na ordem. Alguns exemplos antigos podem depender de APIs descontinuadas, caminhos locais ou acesso à internet.

## Organização e créditos

Este repositório reúne material de estudo de diferentes origens. Consulte os créditos e a licença da fonte original de cada notebook e dataset antes de redistribuir ou reutilizar. Os dados devem manter suas atribuições originais.

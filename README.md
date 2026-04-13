[projeto_validador_v2.zip](https://github.com/user-attachments/files/26663564/projeto_validador_v2.zip)
 🛡️ Validador de Documentos CLI
CI Pipeline

 📌 O Problema (Dor Real)

Muitas aplicações de cadastro e sistemas de gestão sofrem com a entrada de dados inconsistentes ou falsos, especialmente em campos de identificação como o CPF. Dados inválidos geram erros em processos fiscais, bancários e de entrega, causando retrabalho e prejuízo operacional para empresas e desenvolvedores.

 💡 A Solução

Uma aplicação via Linha de Comando (CLI) robusta que utiliza o algoritmo de cálculos de dígitos verificadores da Receita Federal para validar CPFs. O sistema limpa caracteres especiais automaticamente e verifica a integridade matemática do documento, garantindo que apenas dados válidos avancem no fluxo.

 🛠️ Tecnologias Utilizadas

* **Linguagem:** Python 3
* **Testes:** Pytest
* **Linting:** Flake8
* **CI/CD:** GitHub Actions
* **Versionamento:** SemVer (v1.0.0)

 🚀 Como Executar o Projeto

Execute a aplicação CLI no seu terminal:
`python src/validator.py`

 🧪 Como rodar Testes e Linting

1. Instale as dependências: `pip install -r requirements.txt`
2. Para verificar a qualidade do código (Linting): `flake8 src/ tests/`
3. Para rodar os testes automatizados: `pytest tests/`

 👤 Autor

Gabriel Barbosa
**Versão:** 1.0.0

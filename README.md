📊 Automação de Relatórios de Vendas
Aplicação desenvolvida em Python para automatizar a análise e o envio de relatórios de vendas para cada gerente de loja em diferentes shoppings do Brasil.

A ferramenta processa dados de vendas, compara com as metas estipuladas e gera e-mails personalizados informando o desempenho de cada loja.

✨ Funcionalidades
✅ Processamento Automático de Dados — Leitura e tratamento de planilhas de vendas.
✅ Comparação com Metas — Avaliação de desempenho (acima ou abaixo da meta).
✅ Geração de Relatórios Personalizados — Informações individuais para cada gerente.
✅ Envio Automático de E-mails — Comunicação direta e personalizada com cada unidade.

🛠 Tecnologias Utilizadas
🐍 Python — Linguagem principal do projeto.

📊 Pandas — Manipulação e análise dos dados.

📄 OpenPyXL — Manipulação de planilhas Excel.

📧 Smtplib / EmailMessage — Envio automatizado de e-mails.

📂 Estrutura do Projeto
bash
Copiar
Editar
├── dados/                  # Arquivos de vendas
├── src/                    # Código-fonte
│   ├── processa_dados.py
│   ├── gera_relatorio.py
│   ├── envia_email.py
├── README.md               # Documentação
├── requirements.txt        # Dependências
⚙️ Como Executar
1️⃣ Clone o repositório

bash
Copiar
Editar
git clone https://github.com/seu-usuario/seu-repositorio.git
2️⃣ Instale as dependências

bash
Copiar
Editar
pip install -r requirements.txt
3️⃣ Adicione os arquivos de vendas na pasta dados/

4️⃣ Execute o script principal

bash
Copiar
Editar
python src/main.py
📧 Exemplo de E-mail Gerado
Assunto: Relatório de Vendas - Loja Shopping X

Olá [Nome do Gerente],

As vendas da sua loja no mês foram de R$ XX.XXX,XX, com meta de R$ XX.XXX,XX.
Resultado: Acima da meta! 🎉 Parabéns pelo excelente desempenho!

Atenciosamente,
Equipe de Análise

📌 Observações
Os dados utilizados no projeto são fictícios e servem apenas para fins de estudo e demonstração.

Este projeto foi desenvolvido seguindo as práticas aprendidas nos cursos da Hashtag Treinamentos.


<img width="1536" height="1024" alt="ChatGPT Image 12 de ago  de 2025, 18_43_19" src="https://github.com/user-attachments/assets/05357488-b7b1-4743-9392-c8fa7efdc6bd" />


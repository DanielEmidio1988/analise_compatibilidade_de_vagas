# Desafio Alura - Analise e Compatibilidade de Vagas
![Colab](https://img.shields.io/badge/Colab-F9AB00?style=for-the-badge&logo=googlecolab&color=525252)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![Google Gemini](https://img.shields.io/badge/Google%20Gemini-8E75B2.svg?style=for-the-badge&logo=Google-Gemini&logoColor=white)

## 💡 Introdução
Em meio à busca por uma nova oportunidade no mercado de trabalho, é comum encontrar obstáculos que podem tornar o processo frustrante. Desde a concorrência acirrada até os processos seletivos prolongados, diversos fatores podem dificultar essa jornada.

Com o intuito de simplificar essa busca, desenvolvemos este projeto para agilizar a análise das vagas disponíveis. Aqui, o usuário poderá comparar seu currículo com as oportunidades listadas em uma planilha, identificando aquelas que melhor se alinham ao seu perfil. Dessa forma, é possível direcionar esforços para as vagas mais adequadas, aumentando as chances de sucesso.

As informações utilizadas neste projeto foram obtidas a partir de fontes públicas, especificamente da seção de Vagas do LinkedIn, sendo empregadas como teste.

## 👥 Equipe
| [<img src="https://avatars.githubusercontent.com/u/111311678?v=4" width=115><br><sub>Daniel Emidio</sub>](https://github.com/DanielEmidio1988) |
| :---: |

## 🧭 Status do Projeto

<ul>
    <li>⏳Concluído</li>
</ul>


## ⚙️ Configurações

### Instalação do projeto
- Acesse o <a href="https://aistudio.google.com/app/prompts/new_chat?utm_source=website&utm_medium=referral&utm_campaign=Alura&utm_content=" target="_blank">Google AI Studio</a> e clique na opção <b>Get API Key</b> no menu esquerdo;
- Clique na opção <b>Create API Key</b> para gerar sua chave API e salve ela; <i>(Obs: não compartilhe essa chave)</i>
- Abra uma nova janela no <a href="https://colab.google/" target="_blank">Google Colab</a> e faça um novo cadastro (caso não tenha);
- Caso já possua login e senha no Google Colab, digite <b>colab.new</b> no seu navegador do Chrome para abrir um novo projeto no Colab;
- No menu <b>Arquivo</b> clique na opção <b>Fazer upload de notebook</b> e clique em <b>Procurar</b>, selecione o arquivo 'Analise_Compatibilidade_de_Vagas.ipynb';
- No icone de 'Chave' no menu esquerdo, insira 'SECRET_KEY' e no campo 'Valor', insira a chave API que você gerou mais cedo no Google AI Studio e habilite a opção 'Acesso ao notebook';
- No icone de pasta, insira o arquivo .csv de vagas com campo de 'Vaga' e 'Descrição', <b>se necessário, altere o nome do arquivo CSV no seguinte trecho de linha de código do Colab <i>df = pd.read_csv('lista_de_vagas.csv')</i></b>
- A partir da linha 'Configurações iniciais', aperte play em cada uma das linhas de código;
- Ao chegar no campo 'Análise de Dados', insira as informações do seu currículo para análise. Quanto mais completo as informações do seu curriculo, melhor.
- A partir desta análise, você receberá o percentual de compatibilidade entre o seu perfil e a vaga análisada.

## 📫 Contato

E-mail: emidio.daniel@hotmail.com

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/danielemidio1988/)

#  Análise Global de Vendas de Videogames (Business Intelligence)

## O Desafio de Negócio
Fui contratado de forma fictícia por uma publicadora de jogos europeia que deseja expandir suas operações globais. O objetivo da análise foi investigar o histórico de vendas de videogames para responder a três perguntas cruciais para o time de marketing:
1. Quais gêneros são mais rentáveis?
2. Como se comporta o ciclo de vida dos consoles clássicos vs modernos?
3. Quais são as diferenças de consumo entre a América do Norte, Europa e Japão?

## Ferramentas Utilizadas
* **Banco de Dados & SQL:** Extração e limpeza de dados (ETL). Tratamento de valores nulos e criação de Views.
* **Microsoft Power BI:** Criação de painel interativo, modelagem de dados e DAX.

##  A Limpeza dos Dados (ETL em SQL)
Antes de construir o painel, a base de dados bruta (com mais de 16 mil registros) precisou ser tratada. Criei consultas em SQL para remover registros inconsistentes (jogos sem ano de lançamento ou sem publicadora).

Você pode conferir o código SQL completo [clicando aqui no arquivo limpeza_dados.sql].

##  O Dashboard

*Abaixo estão as visualizações criadas para responder ao problema de negócio.*
<img width="1420" height="746" alt="image" src="https://github.com/user-attachments/assets/f445ac43-8bc6-4dbd-af9c-b507ed9a47ce" />
<img width="1412" height="783" alt="image" src="https://github.com/user-attachments/assets/292bad5e-892c-484e-a7fc-bca49a24e727" />


*(Demonstração do painel com filtros por plataforma ativados).*

##  Principais Insights 
Através da análise, as respostas foram as seguintes::
* **Choque Cultural:** Enquanto a América do Norte e a Europa dominam o consumo de jogos de tiro e ação, o mercado Japonês tem uma preferência esmagadora por jogos de **RPG**.
* **A Força da Nostalgia:** O gráfico de linha do tempo revela que consoles como o PS2 tiveram picos de vendas mais altos e duradouros do que muitos hardwares modernos, mostrando uma janela para lançamentos de jogos *Remasterizados*.
* **O Gênero mais Seguro:** Jogos de ação são líderes absolutos de faturamento global, sendo a aposta menos arriscada para novos investimentos da publicadora.

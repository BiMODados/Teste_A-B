# BiMO - Marketplace para MEIs e MEs

**BiMO** é um aplicativo que funciona como um marketplace, criado para auxiliar Microempreendedores Individuais (MEIs) e Microempresas (MEs) na compra e venda de produtos de forma intuitiva e acessível. Além de oferecer uma plataforma de vendas, o app também conta com funcionalidades como chat, fórum, e cursos para maximizar o suporte aos nossos usuários.

## Teste A/B - Interface e Funcionalidade

Para aprimorar a experiência do usuário, realizamos um teste A/B em que foram feitas as seguintes alterações na interface B:

- **NavBar, Chat, Fórum e Carrinho:** Modificamos o layout desses elementos. (Antes vs. Depois)
- **Novo Botão para DashBoard:** Adicionamos um botão específico para facilitar o acesso ao dashboard.
- **Botão de Vendas de Produtos e Cursos:** Redesenhamos o botão para oferecer mais clareza e acessibilidade.

> Nota: Vídeos de cada fluxo podem ser encontrados no diretório `/Fluxos/` sob os nomes `Fluxo_Novo.mp4` e `Fluxo_Antigo.mp4`.

## Roteiro de Testes

O roteiro seguido pelos usuários foi o seguinte:

1. Apresentação do app e explicação do objetivo do teste A/B.
2. Disponibilização de uma prévia no Figma para acompanhamento dos passos abaixo.
3. Realização de um cadastro.
4. Acesso ao anúncio de um produto.
5. Publicação de um produto ou curso.
6. Acesso ao fórum/comunidade e interação com um post.
7. Acesso ao chat e início de uma conversa.
8. Acesso e edição do perfil.
9. Acesso ao dashboard.

## Coleta de Dados

### Fonte Inicial
Inicialmente, usamos a plataforma [Maze](https://maze.co) para realizar e monitorar os testes. No entanto, enfrentamos alguns problemas de execução e baixa adesão, o que prejudicou a qualidade dos dados coletados.

### Fonte Principal
A principal coleta de dados foi realizada em um evento familiar em 03/11/2024, onde conseguimos coletar amostras de 9 participantes para cada interface (A e B). Além disso, dois testes foram aproveitados da plataforma Maze.

Os dados estão armazenados no arquivo `dados_ab_teste.xlsx`.

## Descrição da Base de Dados

A base de dados coletada para análise do Teste A/B contém as seguintes colunas principais:

1. **Tempo:** Tempo total de execução das tarefas (em horas, minutos ou segundos) para cada usuário em uma interface específica.
2. **Interface:** Indica a interface usada pelo usuário (A ou B).
3. **Gênero:** Gênero do usuário (ex.: Masculino, Feminino).
4. **Tempo (seg):** Tempo padronizado em segundos, para facilitar a análise comparativa.

## Análise de Teste-T

As análises do teste-t podem ser encontradas nos notebooks:
- `TesteA-B-Com-Outlier.ipynb`
- `TesteA-B-Sem-Outlier.ipynb`

Ambos os arquivos estão localizados no diretório `/Testes/` e contêm a análise estatística de desempenho das interfaces.

---

Esperamos que o resultado deste teste nos ajude a identificar melhorias na interface do BiMO, proporcionando uma experiência ainda mais eficiente para nossos usuários.

<h2>Criadores:</h2>
<ul>
<li><strong>Marcus Vinicius Righeto Thomazetti</strong> - <a href="https://github.com/MarcusVinciusRT">GitHub</a></li>
<li><strong>Davi De Siqueira Cavalcante</strong> - <a href="https://github.com/davaslindo">GitHub</a></li>
</ul>
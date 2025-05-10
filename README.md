# Trabalho Prático - Semana 11 

**Páginas de detalhes dinâmicas**

Nessa etapa, vamos evoluir o trabalho anterior, acrescentando a página de detalhes, conforme o  projeto escolhido. Imagine que a página principal (home-page) mostre uma visão dos vários itens que existem no seu site. Ao clicar em um item, você é direcionado para a página de detalhes. A página de detalhe vai mostrar todas as informações sobre o item do seu projeto – seja esse item uma notícia, filme, receita, lugar turístico ou evento.

## Informações Gerais

- **Nome:** Pedro Augusto Niess Ferreira  
- **Matrícula:** 1540911  
- **Proposta de projeto escolhida:** Site de Receitas  
- **Breve descrição do projeto:**  
  Este projeto é um site de receitas onde os usuários podem explorar uma lista de pratos. A página inicial exibe receitas em cards dinâmicos, com imagem, nome e descrição. Ao clicar em uma receita, o usuário é direcionado à página de detalhes, contendo informações completas sobre ingredientes e preparo.

---

## Print da versão responsiva com CSS puro

(./public/CapturadeTela.png)

---

## Etapa 2 – Montagem da Estrutura de Dados e Teste da API com JSON Server

A API da aplicação foi criada com o uso do **JSON Server**, utilizando um arquivo `db.json` com uma estrutura de dados representando receitas.

### Exemplo de estrutura inserida no `db.json`:

Print da tela mostrando o retorno do JSON Server:

(./public/APIreturn.png)

```json
{
  "receitas": [
    {
      "id": 1,
      "nome": "Brigadeiro",
      "tempoPreparo": "30 minutos",
      "ingredientes": ["leite condensado", "chocolate", "manteiga"]
    },
    {
      "id": 2,
      "nome": "Bolo de Cenoura",
      "tempoPreparo": "50 minutos",
      "ingredientes": ["cenoura", "farinha", "açúcar", "ovos"]
    },
    {
      "id": 3,
      "nome": "Pudim",
      "tempoPreparo": "1 hora",
      "ingredientes": ["leite", "ovos", "açúcar", "leite condensado"]
    }
  ]
}

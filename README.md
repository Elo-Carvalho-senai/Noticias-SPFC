# Portal de Notícias – São Paulo FC  
Projeto desenvolvido para a Sprint 3 do curso de Desenvolvimento de Sistemas – SENAI

## 1.0 Introdução  
Este projeto consiste na criação de um portal de notícias temático sobre o São Paulo Futebol Clube (SPFC), contendo três páginas principais: **Home**, **Notícia** e **Contato**. Cada página utiliza HTML5 semântico, CSS responsivo e boas práticas de organização estrutural.

O objetivo foi simular um portal profissional, aplicando conceitos de front-end, usabilidade e estruturação de conteúdo.

---

## 2.0 Estrutura do Projeto  

### • index.html — Página inicial  
Contém:
- Navbar personalizada com o tema do SPFC  
- Hero com logo e título  
- Grid de notícias  
- Sidebar com categorias, notícias mais lidas e vídeo incorporado

### • noticia.html — Página de notícia  
Contém:
- Artigo completo com títulos hierárquicos  
- Parágrafos formatados com **strong**, *em*, sub e sup  
- Imagens com atributos otimizados  
- Glossário em lista de definição  
- Tabela com mesclagem de células  
- Links externos e download de PDF  

### • contato.html — Página de contato  
Contém:
- Formulário completo com:  
  - Campos de texto  
  - Email com validação HTML5  
  - Telefone com regex  
  - Área de mensagem  
  - Select de assunto  
  - Radios e checkbox  
  - Upload de arquivo  
- Tabela com horários de atendimento  

### • style.css  
Arquivo único com:
- Reset inicial  
- Estilização da navbar  
- Layout flex e grid  
- Comentários explicando cada parte  
- Responsividade  
- Estilo adicional para página de notícia  
- Estilo adicional para formulário de contato

---

## 3.0 Tecnologias Utilizadas  
- **HTML5** (semântica aplicada)  
- **CSS3** (grid, flexbox, responsividade)  
- **YouTube Embeds**  
- **Validações HTML5 (pattern, required)**  

---

## 4.0 Protótipo no Figma  
Antes do desenvolvimento, foi criado um protótipo visual no **Figma**, definindo:

- A paleta de cores (baseada no vermelho, preto e branco do SPFC)  
- A hierarquia visual (títulos, subtítulos, cards de notícia)  
- O layout inicial das páginas  
- Estrutura da sidebar  
- Distribuição dos elementos na página de contato  

O protótipo ajudou a visualizar:  
- Como as notícias seriam distribuídas  
- Como a navbar ficaria no topo  
- O tamanho do logo no hero  
- A organização dos cards  
- A identidade visual do tema SPFC

Esse processo é essencial para garantir **coerência visual**, prever ajustes antes do código e manter padronização entre as páginas.

---

## 5.0 Validações Realizadas

Durante o desenvolvimento, todas as páginas foram testadas e validadas para garantir qualidade, desempenho, semântica e acessibilidade.

✔ HTML5 Validado

Estrutura revisada com ferramentas de validação.

Tags devidamente fechadas e aninhamento correto.

Atributos obrigatórios definidos (ex.: alt, href, type).

Uso adequado de tags semânticas: header, section, article, footer.

Conteúdo organizado de forma lógica e acessível para leitores de tela.

✔ CSS3 Validado

Responsividade testada em desktop, tablet e mobile.

Grid e Flexbox funcionando corretamente.

Paleta e estilos coerentes com a identidade visual do SPFC.

Comentários claros para facilitar manutenção.

✔ Acessibilidade

Imagens com descrições significativas.

Hierarquia de títulos correta (h1 → h2 → h3).

Contraste adequado entre texto e fundo.

Links identificáveis e acessíveis.

Layout responsivo garantindo boa navegação em qualquer dispositivo.

✔ Formulário validado

Campos obrigatórios utilizando required.

Select, radio e checkbox funcionalmente testados.

Upload de arquivo habilitado e testado.

## 6.0 Como Executar o Projeto

Este projeto é totalmente estático e não exige servidor ou instalação de dependências.

Baixe todos os arquivos do repositório.

Mantenha a organização das pastas conforme o projeto (principalmente /img e /downloads).

Abra o arquivo index.html diretamente no navegador.

Utilize o menu superior para navegar entre as páginas.

O site funciona perfeitamente apenas com HTML + CSS.

## 7.0 Referências Bibliográficas

W3Schools – HTML & CSS Documentation

MDN Web Docs – HTML, CSS e Formulários

Site Oficial do São Paulo FC – Identidade visual e conteúdo temático

YouTube Player API – Parâmetros de incorporação

SENAI – Diretrizes da Sprint 


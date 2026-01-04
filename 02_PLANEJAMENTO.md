_Descomplica - Prática Integradora_

_Desenvolvimento de Software_

# Planejamento

## Site de eventos de tecnologia – Agenda Tecnológica

Este documento descreve o planejamento, as etapas e os itens de verificação para o desenvolvimento do projeto **Agenda Tecnológica**, utilizando HTML, CSS, JavaScript e Bootstrap, conforme os conteúdos abordados na disciplina.

## Objetivo geral

Desenvolver um site responsivo e interativo para inscrição em eventos de tecnologia, aplicando os principais conceitos aprendidos na disciplina, tais como:

- Estruturação de páginas com HTML5 e semântica adequada
- Estilização com CSS e uso do framework Bootstrap
- Manipulação do DOM com JavaScript
- Uso de eventos, arrays e validação de formulários

## Tecnologias utilizadas

- HTML5
- CSS3
- JavaScript
- Bootstrap

## Etapa 1 – Escopo

### Objetivo

Definir o escopo do projeto e a navegação entre as páginas.

### Checklist

- [x] Definir o tipo de eventos
- [x] Definir o público-alvo
- [x] Listar as funcionalidades principais do site
- [ ] Criar wireframe das páginas principais
- [ ] Planejar a navegação entre as páginas

### Descrição

O tipo de eventos é **Tecnologia**, sendo o público-alvo os **profissionais e entusiastas da área de tecnologia**.

O projeto não conta com um backend, todos os dados são salvos no lado do cliente usando `localStorage`.

Eventos possuem:

- Título
- Descrição
- Imagem
- Data: apenas um dia
- Horário: início e término
- Categoria: oficina, curso, palestra ou encontro
- Local
  - Presencial: endereço físico
  - Remoto: URL de chamada
  - Híbrido: endereço físico e URL de chamada

Principais funcionalidades por página:

- Home
  - Listar eventos em destaque: 10 eventos de hoje em diante
  - FAQ
- Eventos
  - Listar todos os eventos
  - Filtrar eventos por:
    - Categoria
    - Data
    - Nome
    - Tipo de local
- Evento
  - Formulário de inscrição
    - Nome, sobrenome e email
    - Validação
  - Cancelamento com modal de confirmação
- Usuário
  - Listar eventos inscritos
  - Cancelamento com modal de confirmação
- Administração
  - CRUD de eventos
  - Validação de formulários de criação e edição

## Etapa 2 – Desenvolvimento

### Objetivo

Criar a estrutura das páginas e suas funcionalidades.

### Checklist

- [ ] Adicionar Bootstrap ao projeto
- [ ] Layout base
  - [ ] Header
  - [ ] Footer
- [ ] Implementar modo escuro
- [ ] Página Home
  - [ ] Carousel de eventos
  - [ ] Accordion de FAQ
- [ ] Página Eventos
  - [ ] Forms para filtro
  - [ ] Card de evento
- [ ] Página Evento
  - [ ] Forms para inscrição
- [ ] Página Usuário
- [ ] Página Administração
  - [ ] Forms para criação
  - [ ] Forms para edição

### Descrição

- Criar layout responsivo para dispositivos móveis e desktop
- Testar responsividade em diferentes tamanhos de tela
- Garantir boa legibilidade (cores e contrastes)
- Renderizar eventos dinamicamente no DOM
- Exibir mensagens de erro e sucesso nas validações
- Salvar inscrições no `localStorage`

## Status do Projeto

- [ ] Escopo
- [ ] Desenvolvimento
- [ ] Testes
- [ ] Finalizado

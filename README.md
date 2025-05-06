# CRIAÇÃO-DE-UMA-ARQUITETURA-BASICA-PARA-SISTEMAS-PEQUENOS

App.jsx
 ├── FormularioCliente.jsx
 └── ListaPedidos.jsx

Projeto: Sistema de Delivery
Tipo de Arquiterura: Monolítica
[Interface (Componentes Visuais)]
	      ↓
[Lógica de Negócio (Funções/Estados)]
	      ↓
[Acesso a Dados (LocalStorage, ou API locais/simulados)]
Interface: JSX visível ao usuário.
Lógica de Negócio: validações, manipulação de dados, regras.
Acesso aos Dados: estados (useState()) ou comunicação com serviços/API.
Componentes: FormularioCliente, ListaClientes, App.
Lógica: evitar cadastro com campos vazio. Evitar emails duplicados
Armazenar dados temporariamente no estado.
Próximo Passo:

Refatorar o código
Correção de bugs
Aplicar boas práticas
Separar os componentes por função (formulário, lista, item, etc)
Criar funções reutilizáveis e separadas da interface
Usar estado local (useState) para simular banco de dados mais específico
Evitar colocar regras dentro do JSX diretamente
Comentar código quando necessário


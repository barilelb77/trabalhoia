# trabalhoia
trabalho ia 3B

PROMPT — SISTEMA DE ADMINISTRAÇÃO DE EMBARCAÇÕES E GESTÃO NAVAL
Crie um sistema web completo de administração e gerenciamento de embarcações/navios, com aparência de um software profissional de uma empresa do setor naval.

O sistema deve ser moderno, profissional, responsivo, intuitivo, seguro e funcional.

Não criar apenas um protótipo visual. Criar uma aplicação funcional, com banco de dados, autenticação, permissões, CRUDs, regras de negócio, controle de estoque, movimentações, manutenção, relatórios e auditoria.

IDENTIDADE DO SISTEMA
Criar uma identidade visual profissional relacionada ao setor naval.

Cores principais:

Azul-marinho.
Azul.
Branco.
Cinza.
Verde para operações normais.
Amarelo para alertas.
Vermelho para situações críticas.
A interface deve transmitir confiança, organização, tecnologia e segurança.

1. SITE INSTITUCIONAL
Criar uma página inicial pública da empresa antes do acesso ao sistema.

A página deve conter:

Logo da empresa.
Nome da empresa.
Menu de navegação.
Início.
Sobre nós.
Serviços.
Gestão de embarcações.
Soluções.
Contato.
Botão "Acessar Sistema".
Criar uma apresentação profissional da empresa voltada para:

Gestão naval.
Administração de embarcações.
Controle de estoque.
Manutenção.
Gestão de materiais.
Logística marítima.
O botão "Acessar Sistema" deve direcionar para a tela de login.

2. LOGIN
Criar uma tela de login profissional.

Campos:

E-mail.
Senha.
Funcionalidades:

Entrar.
Lembrar acesso.
Recuperar senha.
Alterar senha.
Logout.
Controle de sessão.
Proteção das páginas administrativas.
3. DASHBOARD
Após o login, apresentar o painel administrativo.

Exibir:

Total de embarcações.
Embarcações ativas.
Embarcações em operação.
Embarcações em manutenção.
Embarcações inativas.
Total de produtos.
Produtos com estoque baixo.
Produtos sem estoque.
Valor total do estoque.
Manutenções pendentes.
Manutenções atrasadas.
Criar gráficos de:

Entradas de estoque.
Saídas de estoque.
Consumo por embarcação.
Produtos mais utilizados.
Estoque por categoria.
Custos por embarcação.
Manutenções por período.
Criar área de:

Últimas movimentações.
Últimas entradas.
Últimas saídas.
Alertas.
Manutenções próximas.
Atividades recentes.
Permitir filtro por período.

4. EMBARCAÇÕES
Criar módulo completo de gerenciamento de embarcações.

Campos:

Nome da embarcação.
Código interno.
IMO.
MMSI.
Tipo de embarcação.
Bandeira.
Porto de registro.
Capacidade.
Ano de construção.
Fabricante.
Modelo.
Status.
Data de cadastro.
Observações.
Foto da embarcação.
Status:

Ativa.
Em operação.
Em manutenção.
Inativa.
Desativada.
Regras:

Código deve ser único.
IMO deve ser único quando informado.
MMSI deve ser único quando informado.
Permitir:

Criar.
Editar.
Visualizar.
Pesquisar.
Filtrar.
Ordenar.
Desativar.
Excluir quando permitido.
Consultar histórico.
5. DETALHES DA EMBARCAÇÃO
Criar uma página exclusiva para cada embarcação.

Utilizar abas:

Informações
Mostrar todos os dados da embarcação.

Estoque
Mostrar os produtos disponíveis na embarcação.

Colunas:

Produto.
Código.
Categoria.
Quantidade.
Unidade.
Estoque mínimo.
Status.
Movimentações
Mostrar:

Entradas.
Saídas.
Transferências.
Manutenções
Mostrar:

Manutenções planejadas.
Manutenções em andamento.
Manutenções concluídas.
Manutenções atrasadas.
Documentos
Permitir anexar:

Certificados.
Documentação.
Laudos.
Relatórios.
Manuais.
Custos
Mostrar:

Produtos utilizados.
Custos de manutenção.
Custos operacionais.
6. PRODUTOS
Criar módulo completo de produtos.

Cada produto deverá possuir:

Nome do produto.
Código do produto.
Categoria.
Subcategoria.
Descrição.
Unidade de medida.
Estoque mínimo.
Estoque máximo.
Fabricante.
Marca.
Modelo.
Número de série.
Código de barras.
Data de validade.
Valor de custo.
Localização.
Observações.
Status.
Unidades:

Unidade.
Litro.
Quilograma.
Metro.
Caixa.
Pacote.
Galão.
Tonelada.
Outro.
O código do produto deve ser único.

Exemplo:

Produto: Filtro de óleo

Código: FIL-00125

Categoria: Manutenção

Unidade: Unidade

Estoque mínimo: 10

Estoque máximo: 50

7. CATEGORIAS
Criar gerenciamento de categorias.

Exemplos:

Peças.
Ferramentas.
Equipamentos.
Lubrificantes.
Combustíveis.
Materiais de limpeza.
Materiais elétricos.
Materiais hidráulicos.
EPIs.
Materiais de manutenção.
Alimentos.
Outros.
Campos:

Nome.
Código.
Descrição.
Status.
Permitir:

Criar.
Editar.
Excluir.
Pesquisar.
8. ESTOQUE
Criar controle completo de estoque.

O estoque deve ser controlado individualmente por local.

Exemplo:

Produto:

Filtro de óleo.

Almoxarifado Central: 20 unidades.

Navio Alpha: 10 unidades.

Navio Beta: 5 unidades.

O sistema deve mostrar:

Estoque total.
Estoque por local.
Estoque por embarcação.
Estoque mínimo.
Estoque máximo.
Nunca permitir estoque negativo.

9. ENTRADA DE ESTOQUE
Criar tela para registrar entrada.

Campos:

Produto.
Código.
Quantidade.
Unidade.
Local de destino.
Fornecedor.
Nota fiscal.
Documento.
Valor unitário.
Valor total.
Data.
Usuário responsável.
Observações.
Ao confirmar:

Validar os dados.
Registrar a movimentação.
Atualizar estoque.
Registrar usuário.
Registrar data e hora.
Registrar histórico.
10. SAÍDA DE ESTOQUE
Criar tela para registrar saída.

Campos:

Produto.
Código.
Quantidade.
Local de origem.
Embarcação.
Setor.
Motivo.
Data.
Usuário.
Observações.
Antes da saída:

Verificar estoque.
Impedir quantidade superior ao estoque.
Exibir confirmação.
Depois:

Reduzir estoque.
Registrar movimentação.
Registrar usuário.
Registrar data e hora.
11. TRANSFERÊNCIA
Permitir transferência entre:

Almoxarifados.
Depósitos.
Embarcações.
Exemplo:

Origem:

Navio Alpha.

Destino:

Navio Beta.

Produto:

Filtro de óleo.

Quantidade:

10 unidades.

A transferência deve:

Verificar estoque da origem.
Reduzir estoque da origem.
Aumentar estoque do destino.
Registrar a transferência.
Registrar data e hora.
Registrar usuário.
Registrar motivo.
Registrar observações.
A operação deve ser transacional para evitar inconsistências.

12. ALMOXARIFADO
Criar módulo de locais de estoque.

Exemplos:

Almoxarifado Central.
Depósito A.
Depósito B.
Navio Alpha.
Navio Beta.
Campos:

Nome.
Código.
Tipo.
Responsável.
Endereço.
Localização.
Status.
Observações.
13. FORNECEDORES
Criar cadastro de fornecedores.

Campos:

Razão social.
Nome fantasia.
CNPJ.
Inscrição estadual.
E-mail.
Telefone.
Endereço.
Número.
Complemento.
Bairro.
Cidade.
Estado.
CEP.
País.
Responsável.
Observações.
Status.
Criar página de detalhes com:

Produtos fornecidos.
Histórico de entradas.
Compras.
Valores.
Documentos.
14. MANUTENÇÃO
Criar módulo completo de manutenção das embarcações.

Campos:

Embarcação.
Código da manutenção.
Tipo.
Descrição.
Prioridade.
Responsável.
Data de abertura.
Data de início.
Data prevista.
Data de conclusão.
Status.
Custo.
Observações.
Tipos:

Preventiva.
Corretiva.
Preditiva.
Inspeção.
Emergencial.
Status:

Planejada.
Aberta.
Em andamento.
Aguardando peças.
Concluída.
Cancelada.
15. PRODUTOS UTILIZADOS NA MANUTENÇÃO
Uma manutenção pode utilizar vários produtos.

Exemplo:

Revisão do motor:

Filtro de óleo — 5 unidades.
Óleo lubrificante — 20 litros.
Filtro de combustível — 2 unidades.
Ao registrar o consumo:

Criar saída de estoque.
Associar a saída à manutenção.
Associar à embarcação.
Registrar custo.
Registrar usuário.
Registrar data.
16. USUÁRIOS
Criar gerenciamento de usuários.

Campos:

Nome.
E-mail.
Telefone.
Cargo.
Perfil.
Status.
Data de cadastro.
Último acesso.
Perfis:

Administrador
Acesso completo.

Gerente
Acesso administrativo, embarcações, estoque, manutenção e relatórios.

Estoquista
Produtos, estoque, entradas, saídas e transferências.

Operador
Consultas e operações autorizadas.

17. PERMISSÕES
Criar sistema granular de permissões.

Permissões:

Visualizar.
Criar.
Editar.
Excluir.
Exportar.
Aprovar.
Registrar movimentação.
Permitir configurar permissões por módulo e por perfil.

18. AUDITORIA
Registrar todas as operações importantes.

Cada registro deve possuir:

Usuário.
Ação.
Módulo.
Registro afetado.
Data.
Hora.
IP, quando disponível.
Dados anteriores.
Dados novos.
Registrar:

Cadastro.
Alteração.
Exclusão.
Entrada.
Saída.
Transferência.
Alteração de estoque.
Manutenção.
Alteração de usuários.
19. ALERTAS
Criar central de alertas.

Alertar:

Estoque abaixo do mínimo.
Produto sem estoque.
Estoque acima do máximo.
Produto próximo do vencimento.
Produto vencido.
Manutenção próxima do prazo.
Manutenção atrasada.
Embarcação com manutenção pendente.
Cores:

Verde = normal.
Amarelo = atenção.
Vermelho = crítico.
20. PESQUISA
Criar pesquisa global.

Pesquisar:

Embarcações.
Produtos.
Código.
Fornecedores.
Manutenções.
Usuários.
Os resultados devem ser agrupados por módulo.

21. FILTROS
Todos os módulos devem possuir filtros adequados.

Permitir filtrar por:

Nome.
Código.
Status.
Categoria.
Embarcação.
Local.
Fornecedor.
Período.
Usuário.
Tipo.
Prioridade.
Adicionar botão para limpar filtros.

22. RELATÓRIOS
Criar módulo completo de relatórios.

Relatórios:

Estoque atual.
Estoque por embarcação.
Estoque por local.
Entradas.
Saídas.
Transferências.
Consumo por embarcação.
Consumo por produto.
Produtos abaixo do mínimo.
Produtos vencidos.
Produtos próximos do vencimento.
Valor do estoque.
Custos por embarcação.
Custos de manutenção.
Histórico de manutenção.
Produtos mais utilizados.
Movimentações por usuário.
Permitir filtros por:

Data.
Embarcação.
Produto.
Categoria.
Local.
Fornecedor.
Exportar:

PDF.
Excel.
CSV.
23. NOTIFICAÇÕES
Criar central de notificações no sistema.

Exemplos:

"Produto FIL-00125 está abaixo do estoque mínimo."

"Manutenção do Navio Alpha vence em 3 dias."

"Produto XYZ está próximo do vencimento."

Permitir:

Marcar como lida.
Marcar todas como lidas.
Filtrar notificações.
24. PÁGINA DE PRODUTO
Criar página detalhada para cada produto.

Mostrar:

Nome.
Código.
Categoria.
Descrição.
Estoque total.
Estoque mínimo.
Estoque máximo.
Localização.
Embarcações.
Entradas.
Saídas.
Transferências.
Fornecedores.
Custos.
Histórico.
25. TABELA DE PRODUTOS
Criar tabela profissional:

Produto	Código	Categoria	Estoque	Mínimo	Localização	Status	Ações

Indicadores:

Verde = estoque normal.
Amarelo = estoque baixo.
Vermelho = sem estoque.
Ações:

Visualizar.
Editar.
Movimentar.
Histórico.
Desativar.
Botão:

+ Novo Produto

26. MOVIMENTAÇÕES
Criar página de movimentações.

Tabela:

Data	Tipo	Produto	Quantidade	Origem	Destino	Usuário	Status

Tipos:

Entrada.
Saída.
Transferência.
Ao clicar em uma movimentação, mostrar todos os detalhes.

27. CONFIGURAÇÕES
Criar página de configurações.

Empresa
Nome.
Logo.
CNPJ.
Endereço.
Telefone.
E-mail.
País.
Estado.
Cidade.
Estoque
Estoque mínimo padrão.
Estoque máximo padrão.
Regras de alerta.
Notificações
Alertas de estoque.
Alertas de validade.
Alertas de manutenção.
28. MENU PRINCIPAL
Criar menu lateral:

Dashboard.
Embarcações.
Estoque.
Produtos.
Categorias.
Entradas.
Saídas.
Transferências.
Locais de estoque.
Fornecedores.
Manutenção.
Relatórios.
Notificações.
Usuários.
Permissões.
Auditoria.
Configurações.
29. BANCO DE DADOS
Criar banco de dados relacional.

Principais tabelas:

users
roles
permissions
role_permissions
vessels
vessel_documents
products
categories
subcategories
suppliers
warehouses
inventory
inventory_movements
stock_transfers
stock_transfer_items
maintenance
maintenance_items
notifications
audit_logs
Utilizar:

Primary Keys.
Foreign Keys.
Índices.
Unique constraints.
Timestamps.
Soft delete quando necessário.
Garantir integridade referencial.

30. REGRAS DE NEGÓCIO
Obrigatoriamente:

Não permitir códigos de produtos duplicados.
Não permitir códigos de embarcação duplicados.
Não permitir IMO duplicado.
Não permitir MMSI duplicado.
Não permitir estoque negativo.
Não permitir saída maior que estoque disponível.
Atualizar estoque automaticamente.
Registrar todas as movimentações.
Manter histórico.
Controlar permissões.
Validar campos obrigatórios.
Confirmar exclusões.
Registrar usuário.
Registrar data e hora.
Controlar estoque por local.
Controlar estoque por embarcação.
Utilizar transações no banco para operações críticas.
Reverter a operação caso ocorra algum erro.
31. SEGURANÇA
Implementar:

Autenticação segura.
Hash de senhas.
Controle de sessão.
Autorização por função.
Proteção de rotas.
Validação frontend/backend.
Sanitização de dados.
Proteção contra operações não autorizadas.
Auditoria.
Controle de acesso.
Nunca deixar senhas ou informações sensíveis expostas no frontend.

32. RESPONSIVIDADE
O sistema deve funcionar em:

Desktop.
Notebook.
Tablet.
Smartphone.
No celular:

Menu adaptável.
Tabelas responsivas.
Cards reorganizados.
Formulários adaptados.
Botões acessíveis.
Navegação simples.
33. EXPERIÊNCIA DO USUÁRIO
Utilizar:

Loading.
Skeleton.
Empty states.
Mensagens de sucesso.
Mensagens de erro.
Confirmações.
Paginação.
Ordenação.
Filtros.
Pesquisa.
Exemplo:

"Entrada realizada com sucesso. 20 unidades do produto FIL-00125 foram adicionadas ao Almoxarifado Central."

34. DADOS INICIAIS
Criar dados de demonstração.

Embarcações:

Navio Alpha.
Navio Beta.
Navio Gamma.
Produtos:

Filtro de óleo.
Filtro de combustível.
Óleo lubrificante.
Luva de proteção.
Cabo elétrico.
Válvula hidráulica.
Categorias:

Manutenção.
Elétrica.
Hidráulica.
EPI.
Ferramentas.
Criar usuários de demonstração para os diferentes perfis.

35. QUALIDADE
Antes de finalizar, verificar:

Todas as páginas funcionam.
Todos os botões possuem funções reais.
Formulários salvam corretamente.
Banco de dados funciona.
Login funciona.
Permissões funcionam.
CRUDs funcionam.
Estoque é atualizado corretamente.
Entradas funcionam.
Saídas funcionam.
Transferências funcionam.
Manutenções funcionam.
Relatórios funcionam.
Filtros funcionam.
Pesquisa funciona.
Responsividade funciona.
Não existem links quebrados.
Não existem botões sem função.
Não existem erros no console.
Não existem inconsistências no estoque.
36. OBJETIVO FINAL
O resultado final deve ser uma plataforma profissional de gestão naval, com site institucional público e painel administrativo privado.

A estrutura deverá funcionar da seguinte maneira:

SITE DA EMPRESA

↓

ACESSAR SISTEMA

↓

LOGIN

↓

DASHBOARD

↓

GESTÃO NAVAL

Embarcações
→ Estoque
→ Produtos
→ Almoxarifado
→ Fornecedores
→ Manutenção
→ Movimentações
→ Usuários
→ Auditoria
→ Relatórios

O projeto deve possuir arquitetura modular e escalável, permitindo adicionar novos recursos no futuro sem reconstruir todo o sistema.

O resultado deve parecer um software empresarial real, e não um simples template ou protótipo. ATENÇÃO FACA SE PROJETO E ME MOSTRE EM FORMA DE UM SITE MANDE O LINK AQUI NO CHATGPT

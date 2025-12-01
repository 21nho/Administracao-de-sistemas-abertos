**Levantamento de Requisitos – Plataforma IFocus (Formulário para Time de Desenvolvimento)**

==============================================================

## A) REQUISITOS TÉCNICOS DA APLICAÇÃO

1. LINGUAGEM PRINCIPAL

* Qual linguagem será usada?
* Qual versão da linguagem?

2. FRAMEWORKS E VERSÕES

* Framework principal do backend:
* Framework do frontend:
* Versões específicas utilizadas:

3. DEPENDÊNCIAS EXTERNAS
   Listar:

* Bibliotecas críticas
* SDKs essenciais
* APIs externas consumidas (ex.: Google APIs, APIs Gov, Firebase etc.)

4. CONTAINERS

* A aplicação usa Docker? (sim/não)
* Vocês vão entregar Dockerfile(s)? (sim/não)
* Quantos serviços/containers existirão?
  (ex.: backend, frontend, worker, job, fila, etc.)

5. BANCO DE DADOS

* Qual banco será utilizado? (MySQL, Postgres, MongoDB, Redis, etc.)
* Necessidade de cache? (Redis/S3)

6. ARMAZENAMENTO

* A aplicação gera arquivos? (sim/não)
* Quais tipos de arquivos?
* Tamanho típico de cada arquivo?
* Onde precisam ser armazenados? (local, S3, etc.)

==============================================================

## B) REQUISITOS NÃO-FUNCIONAIS (DESEMPENHO, ESCALA, SEGURANÇA)

1. TEMPO DE RESPOSTA

* Qual o tempo máximo de resposta aceitável para o usuário?
  (ex.: até 200ms, 500ms, 1s)

2. CARGA DE USUÁRIOS

* Quantos usuários simultâneos no início do projeto?
* Quantos usuários simultâneos no pico esperado?
* Quantos usuários ativos mensais previstos?

3. REQUISITOS DE SEGURANÇA

* Como será o login/autenticação? (JWT, OAuth, sistema próprio)
* A aplicação lida com dados sensíveis de menores? (sim/não)
* Há requisitos legais específicos? (LGPD, auditoria, logs sensíveis, etc.)

==============================================================

## C) AMBIENTES TECNOLÓGICOS

1. AMBIENTES NECESSÁRIOS
   A infraestrutura sugere:

* Homologação (testes)
* Produção (público)

Perguntas ao time:

* Precisam de mais algum ambiente além desses?
* O ambiente de desenvolvimento local será baseado em Docker? (sim/não)

2. FREQUÊNCIA DE DEPLOY

* O deploy será contínuo (CI/CD)?
* Deploy apenas sob demanda?
* Necessitam de pipeline automatizado? (GitHub Actions, CodePipeline etc.)

==============================================================

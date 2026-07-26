<div align="center">

# 🚀 ASP.NET Core Developer Roadmap

### .NET 10 • C# 14 • ASP.NET Core 10

Roadmap de estudos para desenvolvimento **Backend com o ecossistema .NET**.

</div>

<br />

> [!NOTE]
> Este roadmap tem como objetivo orientar desenvolvedores sobre **o que aprender**, **em qual ordem aprender** e **quais assuntos podem ser estudados posteriormente**.
>
> Ele não deve ser interpretado como uma lista de tecnologias que precisam ser dominadas antes de começar a trabalhar.

---

## 📌 Legenda

| Nível | Significado |
|---|---|
| 🔴 **Essencial** | Deve saber |
| 🟠 **Importante** | Deve conhecer |
| ⚪ **Opcional / Avançado** | Aprender posteriormente |

<br />

## 🗺️ Visão Geral

TODO

<br />

> [!TIP]
> **Não tente estudar tudo ao mesmo tempo.**
>
> Use o roadmap como uma sequência de evolução. Aprenda os fundamentos, pratique em projetos reais e avance conforme os problemas forem aparecendo.

---

# 🧱 Fundamentos

---

## 01. Fundamentos de Desenvolvimento

> Antes de aprender .NET, é importante conhecer alguns fundamentos que independem de linguagem.

<br />

### 🔴 Git

- [ ] Git
- [ ] Repository
- [ ] Commit
- [ ] Push / Pull
- [ ] Branch
- [ ] Merge
- [ ] Rebase
- [ ] Pull Request
- [ ] Merge Conflict
- [ ] `.gitignore`

#### 🟠 Estratégias de Branch

- [ ] Git Flow
- [ ] GitHub Flow
- [ ] Trunk Based Development

<br />

### 🔴 Internet e HTTP

- [ ] Client / Server
- [ ] IP
- [ ] Porta
- [ ] DNS
- [ ] Domínio
- [ ] HTTP
- [ ] HTTPS
- [ ] TLS

#### Métodos HTTP

- [ ] GET
- [ ] POST
- [ ] PUT
- [ ] PATCH
- [ ] DELETE
- [ ] OPTIONS
- [ ] HEAD

#### Status Codes

- [ ] 1xx
- [ ] 2xx
- [ ] 3xx
- [ ] 4xx
- [ ] 5xx

Entender principalmente:

```text
200 OK
201 Created
202 Accepted
204 No Content

400 Bad Request
401 Unauthorized
403 Forbidden
404 Not Found
409 Conflict
422 Unprocessable Content
429 Too Many Requests

500 Internal Server Error
502 Bad Gateway
503 Service Unavailable
504 Gateway Timeout
```

<br />

### 🔴 APIs e REST

- [ ] O que é uma API
- [ ] REST
- [ ] Resource
- [ ] URI
- [ ] Path
- [ ] Query String
- [ ] Headers
- [ ] Request
- [ ] Response
- [ ] JSON
- [ ] Content-Type
- [ ] Stateless
- [ ] Idempotência

<br />

### 🟠 Estruturas de Dados

- [ ] Array
- [ ] List
- [ ] Stack
- [ ] Queue
- [ ] Hash Table
- [ ] Dictionary
- [ ] HashSet
- [ ] Linked List
- [ ] Tree
- [ ] Graph

<br />

### 🟠 Algoritmos

- [ ] Busca
- [ ] Ordenação
- [ ] Recursividade
- [ ] Complexidade de algoritmos
- [ ] Big O

Exemplos:

```text
O(1)
O(log n)
O(n)
O(n log n)
O(n²)
```

<br />

---

# 💻 Linguagem e Plataforma

---

## 02. C# 14

### 🔴 Fundamentos

- [ ] Variáveis
- [ ] Tipos primitivos
- [ ] Value Types
- [ ] Reference Types
- [ ] Nullable Types
- [ ] Nullable Reference Types
- [ ] Operadores
- [ ] Condicionais
- [ ] Loops
- [ ] Métodos
- [ ] Parâmetros
- [ ] Named Arguments
- [ ] Optional Parameters

<br />

### 🔴 Orientação a Objetos

- [ ] Classes
- [ ] Objetos
- [ ] Construtores
- [ ] Properties
- [ ] Fields
- [ ] Encapsulamento
- [ ] Herança
- [ ] Polimorfismo
- [ ] Abstração
- [ ] Interfaces
- [ ] Classes abstratas

<br />

### 🔴 Collections

- [ ] Array
- [ ] List
- [ ] Dictionary
- [ ] HashSet
- [ ] Queue
- [ ] Stack

<br />

### 🔴 Generics

- [ ] Generic Classes
- [ ] Generic Methods
- [ ] Generic Interfaces
- [ ] Constraints

<br />

### 🔴 LINQ

- [ ] Where
- [ ] Select
- [ ] SelectMany
- [ ] First
- [ ] FirstOrDefault
- [ ] Single
- [ ] SingleOrDefault
- [ ] Any
- [ ] All
- [ ] Count
- [ ] OrderBy
- [ ] ThenBy
- [ ] GroupBy
- [ ] Join
- [ ] Distinct
- [ ] Skip
- [ ] Take

Entender:

- [ ] IEnumerable
- [ ] IQueryable
- [ ] Deferred Execution

<br />

### 🔴 Exceptions

- [ ] try
- [ ] catch
- [ ] finally
- [ ] throw
- [ ] Custom Exceptions
- [ ] Exception Filters

<br />

### 🔴 Async / Await

- [ ] Task
- [ ] Task<T>
- [ ] async
- [ ] await
- [ ] CancellationToken
- [ ] Task.WhenAll
- [ ] Task.WhenAny
- [ ] IAsyncEnumerable
- [ ] Async Streams

Entender a diferença entre:

```text
Concorrência
Paralelismo
Assincronismo
```

<br />

### 🟠 Recursos importantes da linguagem

- [ ] Records
- [ ] Record Structs
- [ ] Structs
- [ ] Enums
- [ ] Tuples
- [ ] Pattern Matching
- [ ] Switch Expressions
- [ ] Extension Methods
- [ ] Delegates
- [ ] Events
- [ ] Lambda Expressions
- [ ] Expression Trees
- [ ] Attributes

<br />

### 🟠 C# moderno

- [ ] Primary Constructors
- [ ] Collection Expressions
- [ ] Required Members
- [ ] Init-only Properties
- [ ] Global Usings
- [ ] File-scoped Namespaces
- [ ] Raw String Literals
- [ ] Generic Math
- [ ] `Span<T>`
- [ ] `ReadOnlySpan<T>`

#### C# 14

- [ ] Extension Members
- [ ] Field-backed Properties com `field`
- [ ] Null-conditional Assignment
- [ ] Unbound Generic Types com `nameof`
- [ ] Conversões implícitas para `Span<T>` e `ReadOnlySpan<T>`
- [ ] Modificadores em parâmetros Lambda (`ref`, `in`, `out`, `scoped`, `ref readonly`)
- [ ] Partial Constructors
- [ ] Partial Events
- [ ] User-defined Compound Assignment Operators
- [ ] Novas diretivas de pré-processador para File-based Apps

<br />

---

## 03. Ecossistema .NET 10

### 🔴 Conceitos

Entender a diferença entre:

- [ ] .NET
- [ ] SDK
- [ ] Runtime
- [ ] CLR
- [ ] JIT
- [ ] Garbage Collector
- [ ] NuGet

<br />

### 🔴 Estrutura de projetos

- [ ] Solution
- [ ] Project
- [ ] `.slnx` — formato padrão de solução no .NET 10
- [ ] `.sln` — formato tradicional
- [ ] `.csproj`
- [ ] PackageReference
- [ ] ProjectReference

<br />

### 🔴 .NET CLI

```bash
dotnet new
dotnet restore
dotnet build
dotnet run
dotnet watch
dotnet test
dotnet publish

dotnet package add
dotnet package list
dotnet package remove

dotnet reference add
dotnet reference list
dotnet reference remove
```

> [!NOTE]
> No .NET 10, a CLI passou a oferecer a forma **substantivo primeiro** (`dotnet package add`, `dotnet reference add`).
> Os comandos antigos, como `dotnet add package`, continuam funcionando como aliases.

<br />

### 🟠 File-based Apps

- [ ] Executar aplicações `.cs` sem `.csproj`
- [ ] `dotnet run --file app.cs`
- [ ] `dotnet run app.cs`
- [ ] `dotnet app.cs`
- [ ] `#:package`
- [ ] `#:project`
- [ ] `#:property`
- [ ] `#:sdk`
- [ ] Converter para projeto com `dotnet project convert`

> [!TIP]
> File-based Apps são úteis para scripts, utilitários, exemplos e aplicações pequenas sem a estrutura completa de um projeto tradicional.

<br />

### 🟠 Gerenciamento de memória

- [ ] Stack
- [ ] Heap
- [ ] Garbage Collector
- [ ] GC Generations
- [ ] IDisposable
- [ ] using
- [ ] Finalizers
- [ ] Memory Allocation

<br />

### ⚪ Avançado

- [ ] Reflection
- [ ] Source Generators
- [ ] Native AOT
- [ ] Ahead-of-Time Compilation
- [ ] Assembly
- [ ] IL
- [ ] Roslyn

<br />

---

# 🌐 Desenvolvimento Web

---

## 04. ASP.NET Core 10

### 🔴 Web API

- [ ] Criar uma Web API
- [ ] Controllers
- [ ] Minimal APIs
- [ ] Routing
- [ ] Endpoint Routing
- [ ] Model Binding
- [ ] DTO
- [ ] Request
- [ ] Response
- [ ] Status Codes

<br />

### 🔴 Dependency Injection

- [ ] Dependency Injection
- [ ] Dependency Inversion
- [ ] Constructor Injection
- [ ] IServiceCollection
- [ ] IServiceProvider

#### Lifetimes

- [ ] Transient
- [ ] Scoped
- [ ] Singleton

> [!IMPORTANT]
> Não basta decorar os lifetimes. É importante entender **quando usar cada um** e quais problemas podem surgir ao misturá-los incorretamente.

<br />

---

## 05. Configuration

### 🔴 Configurações

- [ ] appsettings.json
- [ ] appsettings.Development.json
- [ ] Environment Variables
- [ ] IConfiguration
- [ ] Options Pattern
- [ ] IOptions
- [ ] IOptionsSnapshot
- [ ] IOptionsMonitor

<br />

### 🔴 Secrets

- [ ] User Secrets
- [ ] Environment Variables

#### 🟠 Cloud

- [ ] Azure Key Vault
- [ ] AWS Secrets Manager

> [!WARNING]
> Nunca armazene senhas, tokens ou connection strings diretamente no código-fonte.

<br />

---

## 06. ASP.NET Core Pipeline

### 🔴 Middleware

- [ ] Middleware
- [ ] Request Pipeline
- [ ] Middleware customizado
- [ ] Exception Handling Middleware

<br />

### 🔴 Filters

- [ ] Authorization Filter
- [ ] Action Filter
- [ ] Exception Filter
- [ ] Result Filter

<br />

### 🔴 Error Handling

- [ ] Global Exception Handling
- [ ] Problem Details
- [ ] `IProblemDetailsService`
- [ ] RFC 9457
- [ ] RFC 7807 — legado, substituído pelo RFC 9457
- [ ] Padronização de erros

<br />

---

## 07. OpenAPI e Documentação

### 🔴 OpenAPI

- [ ] OpenAPI
- [ ] OpenAPI 3.1
- [ ] `Microsoft.AspNetCore.OpenApi`
- [ ] `AddOpenApi`
- [ ] `MapOpenApi`
- [ ] Documentação de endpoints
- [ ] Request Schema
- [ ] Response Schema

### 🟠 Visualização e documentação interativa

- [ ] Scalar
- [ ] Swagger UI
- [ ] ReDoc
- [ ] Examples
- [ ] API Versioning

### 🟠 Avançado

- [ ] Document Transformers
- [ ] Operation Transformers
- [ ] Schema Transformers

<br />

---

## 08. Validação

### 🔴 Validação nativa

- [ ] Validação de Request
- [ ] Data Annotations
- [ ] `Microsoft.Extensions.Validation`
- [ ] `AddValidation`
- [ ] Validação de parâmetros
- [ ] Validação de tipos
- [ ] Validação de propriedades
- [ ] `IValidatableObject`
- [ ] Validação de regras de negócio

### 🟠 Bibliotecas

- [ ] FluentValidation

> [!IMPORTANT]
> **Validação de entrada** e **regra de negócio** são responsabilidades diferentes.
>
> No ASP.NET Core 10, Minimal APIs possuem suporte nativo à validação com `Microsoft.Extensions.Validation`.

<br />

---

## 09. Segurança

### 🔴 Authentication e Authorization

- [ ] Authentication
- [ ] Authorization
- [ ] JWT
- [ ] Claims
- [ ] Roles
- [ ] Policies

<br />

### 🟠 Identity

- [ ] ASP.NET Core Identity
- [ ] OAuth 2.0
- [ ] OpenID Connect
- [ ] Identity Providers

Exemplos:

- Microsoft Entra ID
- Keycloak
- Auth0
- OpenIddict

<br />

### 🔴 Segurança de APIs

- [ ] CORS
- [ ] CSRF
- [ ] XSS
- [ ] SQL Injection
- [ ] Command Injection
- [ ] Mass Assignment
- [ ] Broken Authentication
- [ ] Broken Access Control
- [ ] Rate Limiting

<br />

### 🔴 OWASP

- [ ] OWASP Top 10
- [ ] OWASP API Security Top 10

<br />

---

# 🗄️ Dados e Persistência

---

## 10. SQL

### 🔴 Fundamentos

- [ ] SELECT
- [ ] INSERT
- [ ] UPDATE
- [ ] DELETE
- [ ] WHERE
- [ ] ORDER BY
- [ ] GROUP BY
- [ ] HAVING

<br />

### 🔴 JOIN

- [ ] INNER JOIN
- [ ] LEFT JOIN
- [ ] RIGHT JOIN
- [ ] FULL JOIN

<br />

### 🔴 Modelagem

- [ ] Primary Key
- [ ] Foreign Key
- [ ] Unique Constraint
- [ ] Check Constraint
- [ ] Normalização
- [ ] Relacionamentos

<br />

### 🔴 Performance

- [ ] Index
- [ ] Execution Plan
- [ ] Composite Index
- [ ] Query Performance
- [ ] N+1 Queries

<br />

### 🔴 Transactions

- [ ] ACID
- [ ] Commit
- [ ] Rollback
- [ ] Isolation Levels
- [ ] Locks
- [ ] Deadlocks

<br />

---

## 11. Bancos de Dados

### 🔴 Relacionais

Aprender pelo menos um muito bem:

- [ ] SQL Server
- [ ] PostgreSQL

Conhecer:

- [ ] MySQL
- [ ] MariaDB
- [ ] Oracle

<br />

### 🟠 NoSQL

- [ ] MongoDB
- [ ] Redis
- [ ] Cosmos DB
- [ ] DynamoDB

### 🟠 Search Engines / Full-Text Search

#### Conceitos

- [ ] Full-Text Search
- [ ] Inverted Index
- [ ] Relevance / Ranking
- [ ] Tokenization
- [ ] Indexação
- [ ] Sincronização entre banco e índice

#### Ferramentas

Conhecer pelo menos uma:

- [ ] Elasticsearch
- [ ] OpenSearch
- [ ] Meilisearch

> [!TIP]
> Mais importante do que decorar bancos e ferramentas diferentes é entender **quando usar SQL, NoSQL, cache ou um mecanismo de busca**.

<br />

---

## 12. Entity Framework Core 10

### 🔴 Fundamentos

- [ ] DbContext
- [ ] DbSet
- [ ] Entities
- [ ] Configuration
- [ ] Fluent API
- [ ] Migrations

<br />

### 🔴 Relacionamentos

- [ ] One-to-One
- [ ] One-to-Many
- [ ] Many-to-Many

<br />

### 🔴 Queries

- [ ] LINQ to Entities
- [ ] Include
- [ ] ThenInclude
- [ ] Projection
- [ ] Tracking
- [ ] AsNoTracking

<br />

### 🟠 Loading

- [ ] Eager Loading
- [ ] Explicit Loading
- [ ] Lazy Loading

<br />

### 🔴 Performance

- [ ] N+1
- [ ] Projection
- [ ] Pagination
- [ ] AsNoTracking
- [ ] Split Queries
- [ ] Compiled Queries
- [ ] ExecuteUpdate / ExecuteUpdateAsync
- [ ] ExecuteDelete / ExecuteDeleteAsync
- [ ] Bulk Operations com bibliotecas externas

<br />

### 🟠 Recursos avançados

- [ ] Transactions
- [ ] Optimistic Concurrency
- [ ] Global Query Filters
- [ ] Named Query Filters
- [ ] Interceptors
- [ ] Value Converters
- [ ] Raw SQL

<br />

---

## 13. Dapper

### 🟠 Importante

- [ ] Query
- [ ] QueryAsync
- [ ] Execute
- [ ] ExecuteAsync
- [ ] Parameters
- [ ] Transactions
- [ ] Multi Mapping

Entender as diferenças entre:

```text
Entity Framework Core
        vs
Dapper
        vs
ADO.NET
```

<br />

---

# 🧠 Qualidade e Arquitetura

---

## 14. Clean Code

### 🔴 Essencial

- [ ] Nomes claros
- [ ] Métodos pequenos
- [ ] Baixo acoplamento
- [ ] Alta coesão
- [ ] Separation of Concerns

Conhecer:

- [ ] DRY
- [ ] KISS
- [ ] YAGNI

### 🟠 Code Quality e Static Analysis

- [ ] `.editorconfig`
- [ ] Roslyn Analyzers
- [ ] Compiler Warnings
- [ ] `TreatWarningsAsErrors`
- [ ] `dotnet format`
- [ ] StyleCop.Analyzers
- [ ] Code Analysis
- [ ] Dependency Vulnerability Scanning

<br />

---

## 15. SOLID

### 🔴 Essencial

- [ ] Single Responsibility Principle
- [ ] Open/Closed Principle
- [ ] Liskov Substitution Principle
- [ ] Interface Segregation Principle
- [ ] Dependency Inversion Principle

> [!TIP]
> O objetivo não é decorar as letras do SOLID. O objetivo é entender **qual problema cada princípio tenta resolver**.

<br />

---

## 16. Design Patterns

### 🟠 Creational

- [ ] Factory
- [ ] Abstract Factory
- [ ] Builder
- [ ] Singleton

### 🟠 Structural

- [ ] Adapter
- [ ] Decorator
- [ ] Facade
- [ ] Proxy

### 🟠 Behavioral

- [ ] Strategy
- [ ] Chain of Responsibility
- [ ] Observer
- [ ] Mediator
- [ ] Command

> [!NOTE]
> Não utilize Design Patterns apenas porque eles existem. Utilize-os quando houver um problema que justifique sua utilização.

<br />

---

## 17. Arquitetura

### 🔴 Essencial

- [ ] Separation of Concerns
- [ ] Layered Architecture
- [ ] Dependency Rule
- [ ] Modularização

### 🟠 Importante

- [ ] Clean Architecture
- [ ] Onion Architecture
- [ ] Hexagonal Architecture
- [ ] Vertical Slice Architecture
- [ ] Modular Monolith

### ⚪ Avançado

- [ ] Domain-Driven Design
- [ ] CQRS
- [ ] Event Driven Architecture
- [ ] Event Sourcing

<br />

---

## 18. Domain-Driven Design

### ⚪ Avançado

- [ ] Domain
- [ ] Subdomain
- [ ] Bounded Context
- [ ] Ubiquitous Language
- [ ] Entity
- [ ] Value Object
- [ ] Aggregate
- [ ] Aggregate Root
- [ ] Domain Service
- [ ] Domain Event
- [ ] Repository

<br />

---

# 🧪 Testes

---

## 19. Testes Automatizados

### 🔴 Unit Tests

Escolha inicialmente um framework:

- [ ] xUnit

Também existem:

- NUnit
- MSTest

<br />

### 🔴 Conceitos

- [ ] Arrange / Act / Assert
- [ ] Test Isolation
- [ ] Test Double
- [ ] Mock
- [ ] Stub
- [ ] Fake

<br />

### 🟠 Mocking

Escolha um:

- [ ] Moq
- [ ] NSubstitute
- [ ] FakeItEasy

<br />

### 🟠 Assertions

- [ ] FluentAssertions

### 🟠 Fake Data

- [ ] Bogus
- [ ] AutoFixture

<br />

### 🔴 Integration Tests

- [ ] WebApplicationFactory
- [ ] TestServer
- [ ] Testcontainers
- [ ] Respawn

<br />

### 🟠 Architecture Tests

- [ ] NetArchTest
- [ ] ArchUnitNET

### ⚪ Snapshot Testing

- [ ] Verify

### 🟠 Contract Testing

- [ ] Consumer / Provider Contracts
- [ ] Backward Compatibility
- [ ] API Contract Testing

### 🟠 E2E

- [ ] Playwright
- [ ] Selenium

### 🟠 Performance Tests

- [ ] k6
- [ ] JMeter
- [ ] Bombardier
- [ ] NBomber

<br />

---

# 🔌 Integrações e Resiliência

---

## 20. API Clients e Comunicação

### 🔴 HttpClient

- [ ] HttpClient
- [ ] HttpClientFactory
- [ ] Typed Clients
- [ ] Named Clients

<br />

### 🔴 Entender

- [ ] Connection Pool
- [ ] Timeout
- [ ] DNS
- [ ] Socket Exhaustion
- [ ] CancellationToken

<br />

---

## 21. Resiliência

### 🔴 Essencial

- [ ] Timeout
- [ ] Retry
- [ ] Exponential Backoff
- [ ] Circuit Breaker

### 🟠 Importante

- [ ] Rate Limiter
- [ ] Bulkhead
- [ ] Fallback
- [ ] Hedging

Conhecer:

- [ ] Microsoft.Extensions.Http.Resilience
- [ ] Polly

<br />

---

## 22. Idempotência

### 🔴 Essencial

- [ ] Idempotency Key
- [ ] Duplicate Requests
- [ ] Retry seguro
- [ ] Unique Constraints
- [ ] Estado da operação

```text
Cliente envia pagamento
        ↓
API processa
        ↓
Cliente perde a resposta
        ↓
Cliente envia novamente
        ↓
API NÃO pode processar duas vezes
```

<br />

---

## 23. Protocolos e Comunicação

### 🔴 REST

- [ ] REST APIs
- [ ] HttpClient

### 🟠 gRPC

- [ ] Protocol Buffers
- [ ] Unary
- [ ] Server Streaming
- [ ] Client Streaming
- [ ] Bidirectional Streaming

### 🟠 Real Time

- [ ] Server-Sent Events (SSE)
- [ ] SignalR
- [ ] WebSockets

Entender a diferença:

```text
SSE         → comunicação servidor → cliente
WebSockets  → comunicação bidirecional
SignalR     → abstração de comunicação em tempo real
```

### ⚪ GraphQL

- [ ] GraphQL
- [ ] HotChocolate

<br />

---

## 24. Object Mapping

### 🔴 Primeiro

- [ ] Manual Mapping

### 🟠 Depois conheça

- [ ] Mapperly
- [ ] AutoMapper

<br />

---

## 25. Background Processing

### 🔴 Nativo

- [ ] BackgroundService
- [ ] IHostedService

### 🟠 Schedulers

- [ ] Hangfire
- [ ] Quartz.NET

<br />

---

# ⚡ Performance e Cache

---

## 26. Cache

### 🔴 Conceitos

- [ ] Cache
- [ ] Cache Hit
- [ ] Cache Miss
- [ ] TTL
- [ ] Cache Invalidation

### 🔴 Memory Cache

- [ ] IMemoryCache

### 🔴 Distributed Cache

- [ ] IDistributedCache
- [ ] Redis

### 🟠 Hybrid Cache

- [ ] HybridCache
- [ ] L1 / L2 Cache
- [ ] Cache Stampede
- [ ] Serialization
- [ ] Local + Distributed Cache

### 🟠 Patterns

- [ ] Cache Aside
- [ ] Read Through
- [ ] Write Through
- [ ] Write Behind

### 🟠 HTTP Cache

- [ ] Output Cache
- [ ] Response Cache
- [ ] ETag
- [ ] Cache-Control

<br />

---

## 27. Logging

### 🔴 Essencial

- [ ] ILogger
- [ ] Log Levels
- [ ] Structured Logging

Log Levels:

```text
Trace
Debug
Information
Warning
Error
Critical
```

<br />

### 🔴 Structured Logging

Evitar:

```csharp
_logger.LogInformation("Usuário " + userId + " realizou pagamento");
```

Preferir:

```csharp
_logger.LogInformation(
    "Usuário {UserId} realizou pagamento",
    userId);
```

### 🟠 Frameworks

- [ ] Serilog
- [ ] NLog

<br />

---

## 28. Observabilidade

> Os três pilares:
>
> **Logs • Metrics • Traces**

### 🔴 Distributed Tracing

- [ ] Trace
- [ ] Span
- [ ] TraceId
- [ ] CorrelationId

### 🟠 OpenTelemetry

- [ ] Instrumentation
- [ ] Traces
- [ ] Metrics
- [ ] Exporters

### 🟠 Ferramentas

#### Metrics

- [ ] Prometheus
- [ ] Grafana

#### Logs

- [ ] Seq
- [ ] Elasticsearch / ELK

#### Tracing

- [ ] OpenTelemetry
- [ ] Jaeger
- [ ] Zipkin

#### APM

- [ ] Application Insights
- [ ] Datadog
- [ ] Dynatrace

### 🟠 Alerting

- [ ] Alert Rules
- [ ] Thresholds
- [ ] Alert Severity
- [ ] Notification Channels
- [ ] Alert Fatigue
- [ ] SLO-based Alerting

#### Ferramentas

- [ ] Grafana Alerting
- [ ] Alertmanager
- [ ] Azure Monitor Alerts
- [ ] Datadog Monitors

<br />

---

## 29. Health Checks

### 🔴 Essencial

- [ ] Health Checks
- [ ] Liveness
- [ ] Readiness

```text
API
 ├── SQL
 ├── Redis
 ├── Service Bus
 └── API externa
```

> [!IMPORTANT]
> **Liveness ≠ Readiness**

<br />

---

## 30. Performance

### 🔴 Essencial

- [ ] Async I/O
- [ ] Connection Pooling
- [ ] Database Indexes
- [ ] Pagination
- [ ] Caching
- [ ] Compression
- [ ] N+1 Problem

### 🟠 Ferramentas

- [ ] BenchmarkDotNet
- [ ] dotnet-counters
- [ ] dotnet-trace
- [ ] dotnet-dump

### 🟠 Métricas

```text
Throughput
Requests/sec
Latency
P50
P90
P95
P99
Error Rate
CPU
Memory
```

<br />

---

## 31. Concorrência

### 🟠 Aplicação

- [ ] Race Condition
- [ ] Thread Safety
- [ ] Lock
- [ ] SemaphoreSlim
- [ ] ConcurrentDictionary
- [ ] Interlocked

### 🟠 Concorrência distribuída

- [ ] Optimistic Concurrency
- [ ] Pessimistic Lock
- [ ] Distributed Lock

<br />

---

# 📨 Mensageria e Sistemas Distribuídos

---

## 32. Mensageria

### 🔴 Conceitos

- [ ] Message
- [ ] Queue
- [ ] Topic
- [ ] Producer
- [ ] Consumer
- [ ] Publisher
- [ ] Subscriber

### 🔴 Garantias de entrega

- [ ] At-most-once
- [ ] At-least-once
- [ ] Exactly-once / Effectively-once
- [ ] Limitações de Exactly-once
- [ ] Duplicate Detection

> [!IMPORTANT]
> Não trate **Exactly-once** como uma simples configuração do broker.
> Em sistemas distribuídos, consumidores idempotentes e tratamento de duplicidade continuam sendo fundamentais.

### 🔴 Problemas importantes

- [ ] Retry
- [ ] Duplicate Messages
- [ ] Idempotent Consumer
- [ ] Dead Letter Queue
- [ ] Poison Message
- [ ] Ordering

### 🟠 Message Brokers

Aprender pelo menos um:

- [ ] RabbitMQ
- [ ] Azure Service Bus
- [ ] Apache Kafka
- [ ] Amazon SQS

### 🟠 Message Bus

- [ ] MassTransit
- [ ] NServiceBus

<br />

---

## 33. Patterns para Sistemas Distribuídos

### 🟠 Importante

- [ ] Outbox Pattern
- [ ] Inbox Pattern
- [ ] Transactional Outbox
- [ ] Idempotent Consumer
- [ ] Saga Pattern
- [ ] Compensating Transaction

### ⚪ Avançado

- [ ] Event Sourcing
- [ ] CQRS
- [ ] Change Data Capture

<br />

---

# 📦 DevOps

---

## 34. Docker

### 🔴 Essencial

- [ ] Container
- [ ] Image
- [ ] Dockerfile
- [ ] Registry
- [ ] Build
- [ ] Run
- [ ] Ports
- [ ] Volumes
- [ ] Environment Variables
- [ ] Networks

<br />

### 🔴 Docker Compose

Conseguir criar algo semelhante a:

```text
┌───────────────────┐
│ ASP.NET Core API  │
└─────────┬─────────┘
          │
     ┌────┴────┐
     ↓         ↓
 PostgreSQL   Redis
```

### 🟠 Docker

- [ ] Multi-stage Build
- [ ] Health Check
- [ ] Image Layers
- [ ] Image Size
- [ ] Container Security

<br />

---

## 35. CI/CD

```text
Commit
   ↓
Build
   ↓
Unit Tests
   ↓
Integration Tests
   ↓
Security Checks
   ↓
Docker Build
   ↓
Push Image
   ↓
Deploy
```

### 🟠 Ferramentas

Escolha pelo menos uma:

- [ ] GitHub Actions
- [ ] Azure DevOps Pipelines
- [ ] GitLab CI/CD

### 🟠 Conceitos

- [ ] Pipeline
- [ ] Artifact
- [ ] Environment
- [ ] Secrets
- [ ] Variables
- [ ] Approval
- [ ] Rollback

<br />

---

## 36. Cloud

> Não é necessário conhecer todas as clouds. Escolha uma inicialmente.

### 🟠 Azure

- [ ] App Service
- [ ] Container Apps
- [ ] Azure Functions
- [ ] Azure SQL
- [ ] Storage Account
- [ ] Service Bus
- [ ] Key Vault
- [ ] Application Insights
- [ ] Azure Container Registry
- [ ] AKS

### 🟠 AWS

- [ ] EC2
- [ ] ECS
- [ ] EKS
- [ ] Lambda
- [ ] RDS
- [ ] S3
- [ ] SQS
- [ ] SNS
- [ ] Secrets Manager
- [ ] CloudWatch

<br />

---

# 🏗️ Arquitetura Avançada

---

## 37. Microservices

> [!WARNING]
> Aprenda a construir um **bom monólito** antes de construir microservices.

### 🟠 Conceitos

- [ ] Monolith
- [ ] Modular Monolith
- [ ] Microservices

### 🟠 Microservices

- [ ] Service Boundaries
- [ ] Database per Service
- [ ] Synchronous Communication
- [ ] Asynchronous Communication
- [ ] Eventual Consistency
- [ ] Service Discovery
- [ ] API Gateway
- [ ] Distributed Transactions

### 🟠 API Gateway

- [ ] YARP

<br />

---

## 38. Kubernetes

### ⚪ Avançado

> Antes de Kubernetes, domine Docker.

- [ ] Cluster
- [ ] Node
- [ ] Pod
- [ ] ReplicaSet
- [ ] Deployment
- [ ] Service
- [ ] Namespace
- [ ] ConfigMap
- [ ] Secret
- [ ] Ingress
- [ ] Persistent Volume

### ⚪ Kubernetes para aplicações

- [ ] Resource Requests
- [ ] Resource Limits
- [ ] Liveness Probe
- [ ] Readiness Probe
- [ ] Horizontal Pod Autoscaler
- [ ] Rolling Update
- [ ] Rollback

### ⚪ Ferramentas

- [ ] kubectl
- [ ] Helm
- [ ] K9s

<br />

---

## 39. Aspire

### 🟠 Importante

- [ ] Aspire CLI
- [ ] Aspire Dashboard
- [ ] AppHost
- [ ] Service Defaults
- [ ] Integrations
- [ ] Service Discovery
- [ ] OpenTelemetry
- [ ] Health Checks
- [ ] Local Development
- [ ] Local Orchestration
- [ ] Distributed Applications

> O Aspire pode facilitar o desenvolvimento, a orquestração local e a observabilidade de aplicações distribuídas.

<br />

---

## 40. System Design

### 🟠 Fundamentos

- [ ] Scalability
- [ ] Availability
- [ ] Reliability
- [ ] Fault Tolerance
- [ ] Horizontal Scaling
- [ ] Vertical Scaling

### 🟠 Load Balancing

- [ ] Load Balancer
- [ ] Reverse Proxy

### 🟠 Dados

- [ ] Replication
- [ ] Partitioning
- [ ] Sharding

### 🟠 Consistência

- [ ] Strong Consistency
- [ ] Eventual Consistency
- [ ] CAP Theorem

### 🟠 Disponibilidade

- [ ] SLA
- [ ] SLI
- [ ] SLO

### 🟠 Disaster Recovery

- [ ] Backup
- [ ] Restore
- [ ] RPO
- [ ] RTO

<br />

---

## 41. API Design

### 🔴 Essencial

- [ ] Resource Naming
- [ ] HTTP Semantics
- [ ] Status Codes
- [ ] Pagination
- [ ] Filtering
- [ ] Sorting
- [ ] Validation
- [ ] Error Responses

### 🟠 Importante

- [ ] API Versioning
- [ ] Idempotency
- [ ] Rate Limiting
- [ ] Correlation ID
- [ ] OpenAPI
- [ ] Backward Compatibility

<br />

---

## 42. Arquitetura Orientada a Eventos

### ⚪ Avançado

- [ ] Event Notification
- [ ] Event-Carried State Transfer
- [ ] Eventual Consistency
- [ ] Event Schema
- [ ] Event Versioning

<br />

---

# 🤖 IA e Ferramentas Modernas

---

## 43. IA e LLMs

### 🟠 Desenvolvimento

- [ ] GitHub Copilot
- [ ] ChatGPT
- [ ] Claude

Também saber:

- [ ] Revisar código gerado
- [ ] Validar respostas
- [ ] Não enviar secrets
- [ ] Não confiar cegamente em código gerado

### ⚪ Integração com aplicações

- [ ] OpenAI .NET SDK
- [ ] Semantic Kernel
- [ ] Microsoft.Extensions.AI

### ⚪ Conceitos

- [ ] LLM
- [ ] Token
- [ ] Context Window
- [ ] Prompt
- [ ] Embeddings
- [ ] Vector Search
- [ ] RAG
- [ ] Tool Calling / Function Calling

<br />

---

# 🎯 Como Evoluir na Carreira

---

## 44. O que NÃO precisa aprender de uma vez

> [!CAUTION]
> Um roadmap representa uma **jornada**, não uma lista de pré-requisitos para conseguir um emprego.

Você não precisa dominar tudo isto de uma vez:

```text
C#
.NET
SQL
Redis
MongoDB
RabbitMQ
Kafka
Docker
Kubernetes
DDD
CQRS
Azure
AWS
Microservices
OpenTelemetry
Grafana
...
```

<br />

---

# 🧭 Roadmap por Nível

## 🟢 Desenvolvedor Júnior

```text
Git
 ↓
HTTP
 ↓
C#
 ↓
.NET
 ↓
ASP.NET Core
 ↓
REST
 ↓
SQL
 ↓
Entity Framework
 ↓
Dependency Injection
 ↓
SOLID
 ↓
Unit Tests
 ↓
Integration Tests
```

### Checklist

- [ ] Git
- [ ] HTTP
- [ ] C#
- [ ] Orientação a Objetos
- [ ] LINQ
- [ ] Async / Await
- [ ] ASP.NET Core
- [ ] REST API
- [ ] Dependency Injection
- [ ] SQL
- [ ] Entity Framework
- [ ] Unit Tests
- [ ] Integration Tests
- [ ] Docker básico

<br />

---

## 🔵 Desenvolvedor Pleno

```text
Arquitetura
 ↓
Redis
 ↓
Mensageria
 ↓
Resiliência
 ↓
Docker
 ↓
CI/CD
 ↓
Observabilidade
 ↓
Cloud
```

### Checklist

- [ ] Clean Architecture / Vertical Slice
- [ ] Design Patterns
- [ ] Redis
- [ ] HttpClientFactory
- [ ] Resiliência
- [ ] RabbitMQ / Service Bus / Kafka
- [ ] MassTransit
- [ ] Outbox
- [ ] Docker
- [ ] CI/CD
- [ ] OpenTelemetry
- [ ] Cloud
- [ ] Performance

<br />

---

## 🟣 Desenvolvedor Sênior

```text
System Design
 ↓
Sistemas Distribuídos
 ↓
Arquitetura
 ↓
Performance
 ↓
Resiliência
 ↓
Microservices
 ↓
Kubernetes
 ↓
Cloud
```

### Checklist

- [ ] System Design
- [ ] Distributed Systems
- [ ] Eventual Consistency
- [ ] Distributed Transactions
- [ ] Saga
- [ ] Outbox
- [ ] Idempotência
- [ ] Performance
- [ ] Observabilidade
- [ ] Microservices
- [ ] Kubernetes
- [ ] Cloud Architecture
- [ ] Scalability
- [ ] High Availability
- [ ] Disaster Recovery
- [ ] SLA / SLO / SLI

<br />

---

# 🧪 Projeto Sugerido para Aprendizado

> A melhor forma de percorrer o roadmap é evoluir **o mesmo projeto** conforme novos assuntos forem estudados.

---

## Etapa 01 — API Base

Criar uma API de e-commerce:

```text
Customer
Product
Order
Payment
```

Utilizando:

- ASP.NET Core
- C#
- SQL
- Entity Framework Core

<br />

## Etapa 02 — Qualidade da API

Adicionar:

- Validation
- Authentication
- Authorization
- JWT
- Exception Handling
- OpenAPI
- Logging

<br />

## Etapa 03 — Testes

Adicionar:

- Unit Tests
- Integration Tests
- Testcontainers

<br />

## Etapa 04 — Cache

Adicionar Redis:

```text
GET /products/{id}

       ↓

     Redis
       ↓
 Cache Hit?
  ↙       ↘
SIM       NÃO
 ↓         ↓
Return    Database
```

<br />

## Etapa 05 — Processamento Assíncrono

```text
Order API
    │
    ▼
Message Broker
    │
    ├────► Payment Worker
    │
    ├────► Email Worker
    │
    └────► Stock Worker
```

<br />

## Etapa 06 — Resiliência

Adicionar:

- Idempotência
- Retry
- Circuit Breaker
- Dead Letter Queue
- Outbox Pattern

<br />

## Etapa 07 — Containers

```text
Docker Compose

├── API
├── Worker
├── PostgreSQL
├── Redis
└── RabbitMQ
```

<br />

## Etapa 08 — Observabilidade

```text
Application
    │
    ▼
OpenTelemetry
    │
    ├── Logs
    ├── Metrics
    └── Traces
```

<br />

## Etapa 09 — CI/CD

```text
Git Push
   ↓
Build
   ↓
Tests
   ↓
Docker Build
   ↓
Registry
   ↓
Deploy
```

<br />

## Etapa 10 — Arquitetura Avançada

Somente depois avaliar:

```text
Modular Monolith
       ↓
Microservices
       ↓
Kubernetes
```

<br />

---

# 🏆 Objetivo Final

Ao final da trilha, o desenvolvedor deve ser capaz de:

- Projetar uma API
- Implementar utilizando ASP.NET Core
- Modelar um banco de dados
- Utilizar Entity Framework
- Criar testes automatizados
- Implementar autenticação e autorização
- Integrar APIs externas
- Trabalhar com cache
- Trabalhar com mensageria
- Criar aplicações resilientes
- Implementar observabilidade
- Containerizar aplicações
- Criar pipelines CI/CD
- Fazer deploy em cloud
- Diagnosticar problemas de performance
- Entender sistemas distribuídos
- Tomar decisões arquiteturais justificadas

<br />

---

# ⚠️ Observação Importante

Não tente aprender todas as ferramentas deste roadmap.

Por exemplo:

```text
RabbitMQ
Kafka
Azure Service Bus
Amazon SQS
```

Todas estão relacionadas a mensageria, mas um desenvolvedor não precisa dominar todas para entender o conceito.

Da mesma forma:

```text
SQL Server
PostgreSQL
MySQL
Oracle
```

não precisam ser dominados simultaneamente.

> [!TIP]
> Primeiro aprenda **os conceitos**.
>
> Depois aprenda **uma implementação**.
>
> Por fim, conheça **as alternativas**.

<br />

---

# 🧠 Regra de Ouro

<div align="center">

### Conceito → Implementação → Ferramenta

</div>

Evite aprender apenas:

```text
Como usar RabbitMQ?
```

Procure entender primeiro:

```text
Por que existe mensageria?

Qual problema ela resolve?

Quando não devo utilizar?

Quais garantias de entrega existem?

Como lidar com falhas?

Como lidar com mensagens duplicadas?
```

> Ferramentas mudam.
>
> **Fundamentos permanecem.**

<br />

---

# 📚 Referência

Este roadmap foi inspirado e adaptado a partir do projeto:

**ASP.NET Core Developer Roadmap — Moien Tajik**

A estrutura foi reorganizada com foco didático e ordem de aprendizado para formação de desenvolvedores Backend utilizando **C# 14, .NET 10 e ASP.NET Core 10**.

<br />

---

# ⭐ Contribuição

Este roadmap não é uma lista definitiva.

Tecnologias, frameworks e boas práticas evoluem constantemente.

**Contribuições, sugestões e Pull Requests são bem-vindos.**

<br />

---

# 📄 Licença

Este roadmap é uma adaptação do projeto **ASP.NET Core Developer Roadmap**, criado por **Moien Tajik**.

Foram realizadas alterações na estrutura, no conteúdo, na ordem de aprendizado, nas tecnologias apresentadas e no foco didático.

O trabalho original é distribuído sob a licença:

**CC BY-NC-SA 4.0 — Attribution-NonCommercial-ShareAlike 4.0 International**

Esta adaptação deve ser distribuída sob a mesma licença, mantendo a atribuição ao trabalho original e a indicação de que alterações foram realizadas.

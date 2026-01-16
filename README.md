# MultiTenantBarPlatform.Api

Bem-vindo ao BarManager.SaaS, uma plataforma multi-tenant desenvolvida para permitir que donos de bares gerenciem seus produtos, funcionários e vendas de forma simples e eficiente, enquanto um Superadmin controla toda a plataforma.

Este projeto foi criado com foco em boas práticas, escalabilidade e arquitetura limpa.

## Tecnologias Utilizadas

  - C# + ASP.NET Core
  - FastEndpoints
  - JWT Authentication
  - Tenant Resolver Middleware
  - Entity Framework Core
  - PostgreSQL

##  Funcionalidades

### Plataforma (Superadmin)
- Cadastro global de bares
- Ativar / Desativar bares
- Visualizar métricas (futuro)

### Bar (Tenant Admin)
- Gestão de produtos (cadastrar, editar, eliminar)
- Gestão de funcionários (ativar, desativar, editar)
- Visualizar vendas (futuro)

### Funcionário (Caixa)
- Registro de vendas

---

##  Arquitetura do Sistema

- Multi-Tenant (Single DB + TenantId)
- Clean Architecture Clássico
- JWT Auth com Roles e TenantId
- Tenant Resolver Middleware
- EF Core + PostgreSQL

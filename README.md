# Gerenciador de Veículos — Minimal API

Início de uma API de gestão de veículos em **.NET 8 (Minimal API)**, organizada em camadas (`Dominio`, `Infraestrututra`) e preparada para **Entity Framework Core** com MySQL (Pomelo).

## Estado atual

- `GET /` — mensagem de teste.
- `POST /login` — autentica com `{ "email": "...", "senha": "..." }` (credenciais fixas de demonstração; devolve `200` ou `401`).
- `DBContexto` criado, ainda sem entidades.

## Executar

```bash
dotnet run
```

## Próximos passos

Entidades `Administrador` e `Veiculo`, migrações EF, autenticação JWT e CRUD de veículos.

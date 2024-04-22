Temos 2 entidades: `Paciente (user)` e `Unidade Médica (place)`

As informações que precisamso de cada uma:

1. Paciente:

```
- ID (ex.: asd78-1j34-aosidjoas-75asd8)
- Nome (ex.: "Fulana de Tal")
- CPF (ex.: "xxx.yyy.zzz-ww")
- Data de Início da Gestação (ex.: yyyy-mm-dd)
- Tempo de gravidez (calculada pelo sistema)
- Status (ex.: "estável", "instável", "em observação", "normal", etc)
```

2. Unidade Médica:

```
- ID (ex.: asd78-1j34-aosidjoas-75asd8)
- Local (Restrito a Manacapuru) - (ex.: "Bairro do Fonseca")
- Pacientes atendidos (uma lista de IDs dos Pacientes) - (ex.: ["id01","id02","id03","id04","id05", ...])
```

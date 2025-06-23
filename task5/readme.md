# Анализ и решение

В представленном контракте можно выделить следующие ресурсы:

## 1. Данные о клиенте
**Endpoint:** `/clients/{id}`  
**Поля:**
- `id`
- `name`
- `age`

## 2. Данные о документах (связанные с клиентом)
**Endpoint:** `/clients/{id}/documents`  
**Поля:**
- `id`
- `type`
- `number`
- `issueDate`
- `expiryDate`

## 3. Данные о родственниках (связанные с клиентом)
**Endpoint:** `/clients/{id}/relatives`  
**Поля:**
- `id`
- `relationType`
- `name`
- `age`

Новая схема GraphQL приложена в файле [contract.graphql](contract.graphql)
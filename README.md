# 🏁 visit-your-new-home - TypeORM

| HTTP Method | Description                          | Endpoint                    | Authentication Required |
| ----------- | ------------------------------------ | --------------------------- | ----------------------- |
| POST        | Register category                    | `/categories`               | Authenticated           |
| GET         | List categories                      | `/categories`               | No Authentication       |
| GET         | All properties from category         | `/categories/id/realEstate` | No Authentication       |
| POST        | Create property                      | `/realEstate`               | Authenticated           |
| GET         | List all properties                  | `/realEstate`               | No Authentication       |
| POST        | Schedule a visit to a property       | `/schedules`                | Authenticated           |
| GET         | list all appointments for a property | `/schedules/realEstate/id`  | No Authentication       |
| POST        | Register user                        | `/users`                    | No Authentication       |
| GET         | List users                           | `/users`                    | Authenticated           |
| POST        | Login                                | `/login`                    | No Authentication       |
| DELETE      | Soft delete                          | `/users/id`                 | Authenticated           |
| PATCH       | Update user                          | `/users/id`                 | Authenticated           |

## Install dependencies:

```bash
# caso use npm
npm run i

# caso use yarn
yarn
```

## Installation

Only the test libraries, or that the tests depend on, are in **package.json**. Therefore, install the project's dependencies manually and don't forget to start it too.

```bash
# npm
npm init -y

# yarn
yarn init -y
```

## Run tests

Para rodar os testes é necessário que no seu terminal, você esteja dentro do diretório do projeto.

Estando no terminal e dentro do caminho correto, você poderá utilizar os comandos a seguir:

### Run all tests

```bash
# npm
npm run test

# yarn
yarn test
```

### Run all tests with detailed log

```bash
# npm
npm run test --all

# yarn
yarn test --all
```

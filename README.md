# MS SQL Server

Coursework repository for the course **"Database Theory. MS SQL Server Programming"** (Теория баз данных. Программирование MS SQL Server), IT TOP College, group 9/3-RPO-24/1, autumn 2026. Instructor: O. A. Roslova.

It collects all practical assignments and homework completed during the course, along with lecture notes and the instructor's materials.

The course covers database design and normalization, choosing storage for a given workload, working with Microsoft SQL Server and SSMS, T-SQL, programmable objects (procedures, functions, triggers), query performance and security.

## Practical assignments

| # | Folder | Topic | Database |
|---|--------|-------|----------|
| 1 | [`practice_01`](practice_01/README.md) | Data placement in a multi-component system ("Kursator" platform) | — |
| 2 | [`practice_02`](practice_02/README.md) | Mini-project "Electronic Library": design and normalization | — |
| 3 | [`practice_03`](practice_03/README.md) | T-SQL: 3NF schema and test data | `BookStore` |
| 4 | [`practice_04`](practice_04/README.md) | T-SQL: control flow, indexes, execution plans | `BookStore` |
| 5 | [`practice_05`](practice_05/README.md) | Triggers, procedures and functions: e-sports platform | `EsportsDB` |
| 6 | [`practice_06`](practice_06/README.md) | Business logic of an EV car-sharing service | `CarSharingDB` |
| 7 | [`practice_07`](practice_07/README.md) | Security: users, roles, permissions | `MyDB` |

## Homework

| # | Folder | Topic |
|---|--------|-------|
| 1 | [`homework_01`](homework_01/README.md) | MS SQL Server and SSMS basics |
| 2 | [`homework_02`](homework_02/README.md) | What is T-SQL and how it differs from standard SQL |

## Lectures and materials

| Folder | Contents |
|--------|----------|
| [`lectures`](lectures/README.md) | lecture notes: topics, key terms, what was covered in class |
| [`materials`](materials/README.md) | instructor's files: assignment sheets and slides |

## Repository structure

```
msSqlServer/
├── README.md              ← you are here
├── WORK_TEMPLATE.md       README template for a new assignment
├── practice_NN/           practical assignments
│   ├── README.md          assignment description
│   └── report.pdf         report with code and results
├── homework_NN/           homework (same structure)
├── lectures/              lecture notes
└── materials/             instructor's materials, one folder per topic
```

Assignment 1 was done in a separate repository and is included as a git submodule. To clone everything at once:

```bash
git clone --recurse-submodules https://github.com/Ik4rCat/msSqlServer.git
```

## License

The completed work is licensed under the [MIT License](LICENSE). The license does not apply to the contents of the `materials/` folder, which belong to their respective authors.

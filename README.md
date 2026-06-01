# QA Fintech — Parabank Testing Portfolio

## Descripción
Proyecto de QA Manual Testing sobre la aplicación bancaria demo **Parabank** (parabank.parasoft.com). Cubre análisis de requerimientos, diseño y ejecución de casos de prueba, y reporte de defectos.

## Herramientas utilizadas
- **TestRail** — Gestión y ejecución de casos de prueba
- **Notion** — Documentación de casos de prueba y bug reports
- **Google Sheets** — Matriz de pruebas
- **Parabank** — Aplicación bajo prueba (AUT)

## Módulos testeados
| Módulo | TCs | PASS | FAIL | BLOCKED |
|---|---|---|---|---|
| Login | 9 | 2 | 1 | 6 |
| Register | 9 | 7 | 2 | 0 |
| Open Account | 4 | 2 | 2 | 0 |
| Transfer Funds | 5 | 1 | 4 | 0 |
| Bill Pay | 7 | 6 | 1 | 0 |
| Request Loan | 8 | 1 | 7 | 0 |
| **Total** | **42** | **19** | **17** | **6** |

## Bugs encontrados
- **19 bugs documentados** entre severidad Low, Medium, High y Critical
- Incluye bugs críticos de seguridad (autenticación bypass) y datos (SSN con letras)

## Documentación
- 📋 [Casos de prueba en Notion]([https://notion.so](https://www.notion.so/4d62edb43ab44e6580a2b9b94d496c45?v=3701716c9b858194a864000c5884e448&source=copy_link))
- 🐛 [Bug Reports en Notion]([https://notion.so](https://www.notion.so/d2bb9f6782344deea39ef9803d6b9bdb?v=3701716c9b858194a864000c5884e448&source=copy_link))
- 📊 [Reporte TestRail](./testrail-report-parabank-6-1-2026.pdf)

## Autor
**Jose Jimenez** — QA Engineer  
[LinkedIn](https://www.linkedin.com/in/josejimenez07) | [GitHub](https://github.com/engineerqajimenez-jpg)

| Entity                                      | Kardinaliteit |
|---------------------------------------------|---------------|
| `commonTechnical.default`                   | 1..1, V       |
| \|----`party.sender`                        | 1..1, V       |
| \|--------`party.contact`                   | 0..*, O       |
| \|----`party.receiver`                      | 1..1, V       |
| `commonFunctional.default`                  | 1..1, V       |
| `party.pensionProvider`                     | 1..1, V       |
| \|----`pension.scheme`                      | 1..*, V       |
| \|--------`financialInformation.reportingPeriod` | 1..1, V |
| \|--------`pension.cohort`                  | 1..*, O       |
| \|--------`investment.portfolio`            | 1..*, V       |
| `error.default`                             | 0..*, O       |
| `document.default`                          | 0..*, O       |

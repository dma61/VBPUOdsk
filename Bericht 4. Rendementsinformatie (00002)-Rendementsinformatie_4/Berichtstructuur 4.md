| Entity                                      | Kardinaliteit |
|---------------------------------------------|---------------|
| `commonTechnical.default`                   | 1..1, R       |
| &emsp;`party.sender`                        | 1..1, R       |
| &emsp;&emsp;`party.contact`                 | 0..*, O       |
| &emsp;`party.receiver`                      | 1..1, R       |
| `commonFunctional.default`                  | 1..1, R       |
| `party.pensionProvider`                     | 1..1, R       |
| &emsp;`pension.scheme`                      | 1..*, R       |
| &emsp;&emsp;`financialInformation.reportingPeriod` | 1..1, R |
| &emsp;&emsp;`pension.cohort`                | 1..*, O       |
| &emsp;&emsp;`investment.portfolio`          | 1..*, R       |
| `error.default`                             | 0..*, O       |
| `document.default`                          | 0..*, O       |

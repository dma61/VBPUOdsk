| Entity                                                      | Kardinaliteit |
|-------------------------------------------------------------|---------------|
| `commonTechnical.default`                                   | 1..1, R       |
| \|----`party.sender`                                        | 1..1, R       |
| \|--------`party.contact`                                   | 0..*, O       |
| \|----`party.receiver`                                      | 1..1, R       |
| `commonFunctional.default`                                  | 1..1, R       |
| `party.pensionProvider`                                     | 1..1, R       |
| \|----`pension.scheme`                                      | 1..*, R       |
| \|--------`financialInformation.reportingPeriod`            | 1..1, R       |
| \|--------`investment.investmentDetails`                    | 1..*, R       |
| \|------------`financialTransaction.trade`                  | 1..*, R       |
| `error.default`                                             | 0..*, O       |
| `document.default`                                          | 0..*, O       |

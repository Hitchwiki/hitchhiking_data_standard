- [ ] Approved


| Tag         | Importance  | Type    | Description                                                        | Enum                        | Example |
|-------------|-------------|---------|--------------------------------------------------------------------|-----------------------------|---------|
| kind        | required | string  | Kind of gift received.                          | money, food, goods          |         |
| description | optional | string  | Further description of the give received.                          |                             |         |
| value       | optional | float   | Positive decimal number. What is the estimated/ exact value of the gift received? Required if `currency` is given. |                             |         |
| currency    | optional | string  | Currency code. Required if `value` is given. |                                                  |                             |         |

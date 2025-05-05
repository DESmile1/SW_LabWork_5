### Тестові сценарії для функції register()

| FR ID | TC ID | Кроки сценарію                     | Очікуваний результат |
|-------|-------|------------------------------------|----------------------|
| FR1.1 | TC1.1 | username="user1", password="pass1234" | 1                   |
| FR1.1 | TC1.2 | username="1user", password="pass1234" | -1                  |
| FR1.1 | TC1.3 | username="user1", password="123"    | -2                  |

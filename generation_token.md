Генерація Github токена

https://github.com/eleks-bootcamp/education-plan/blob/main/git-module-2/token.md

Переходимо за посиланням https://github.com
Клікаємо на аватарці, вибираємо "Settings"
github-settings

На вкладці "profile" вибираємо "Developer settings"
developer-settings

Клікаємо на "Personal access tokens"
personal-access-tokens

Натискаємо на кеопку "Generate new token"
Заповнюємо поля:
Note: "bootcamp"
Expiration: 90
Вибираємо "repo" checkbox
Клікаємо на "Generate token"
new-token

Копіюємо токен та зберегаємо в надійному місці, повторно скопіювати його буде наможливо
generated-token

Переходимо до вашого форку репозиторія
clone-repo

Копіюємо посилання https://github.com/<посилання на ваш репозиторій>.git
Додаємо токен до посилання https://<ваш токен>@github.com/<посилання на ваш репозиторій>.git
В корні проекта виконуємо команду git remote set-url origin <посиляння з токеном>

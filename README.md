# infra_actions
## Учебный проект для изучения работы GitHub Actions (Яндекс Практикум)
### Позволяет автоматизировать процесс тестирования, проверки кода на соответствие PEP8 и отправку образа на DockerHub
Принцип работы заключается в следующем: при локальном внесении изменений в репозиторий, с последующим коммитом и отправкой, в заданной последовательности запускаются процессы, описанные в файле .github/workflows/main.yml <br>
1. Тестирование проекта. <br>
2. Сборка и публикация образа. <br>
3. Автоматический деплой. <br>
4. Отправка уведомления в персональный чат. <br>

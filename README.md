# Домашнее задание к занятию «Введение в микросервисы» - Тертерян Вячеслав

---

### Задача  

Руководство крупного интернет-магазина, у которого постоянно растёт пользовательская база и количество заказов, рассматривает возможность переделки своей внутренней ИТ-системы на основе микросервисов.

Вас пригласили в качестве консультанта для оценки целесообразности перехода на микросервисную архитектуру.

Опишите, какие выгоды может получить компания от перехода на микросервисную архитектуру и какие проблемы нужно решить в первую очередь.  

# Ответ  

Итак если все упростить, выгоды которые получит компания - это увелечение скорости разработки и публикации нового йункционала в разных направлениях.
Простой способ разделения исходя из-за задачи - это разделить заказы и регистрацию клиентов например, и далее уже можно вычленять более мелкие задачи в отдельные сервисы.
Проблемы необходимо решить:  
- Готовы ли команды разработки и обслуживания к подобным нагрузкам и распределению
- Наладить автоматизацию процессов
- Определится с оркестрацией и принципами соглосования действий
- Четко определить, что выделять в отдельный сервис  

Плюсы:  
- Ускорение разработки и деплоя  
- Развязывания разных систем между собой  
- Повышение стабильности работы, так как каждая система может настраиваться индивидуально в зависимости от угроз выхода из строя
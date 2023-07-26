# Skillfactory-28
Итоговый проект по автоматизации тестирования. Модуль 28
Для тестирования сайта были использованы:

техники эквивалентного разбиения,
причина/следствие анализ граничных значений
Тесты настроены на запуск через терминал python -m pytest -v --driver Chrome --driver-path chromedriver.exe tests_SF_RT.py

base_data.py - базовые классы, процедуры, функции и локаторы для автотестов settings.py - регистрационные данные для позитивных тестов авторизации tests_SF_RT.py - набор автотестов

Объект тесирования: форма регистрации/авторизации сайта: https://b2c.passport.rt.ru

Ссылка на тестирование требований, тест-кейсы, баг-репорты: https://docs.google.com/spreadsheets/d/1Wwuhs7jKwAnt5pbc7E9e7Nzcu4H6TEd-DyImQUR0JDU/edit?usp=sharing

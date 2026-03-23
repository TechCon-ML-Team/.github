<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=18&pause=2000&color=8E8699&background=0D111700&center=true&vCenter=true&width=600&lines=ML-инжиниринг+для+промышленной+инспекции;R%26D+%C2%B7+Разработка+%C2%B7+Продакшн+%C2%B7+MLOps;Речь+%C2%B7+Зрение+%C2%B7+Документы+%C2%B7+Инфраструктура)](https://git.io/typing-svg)

<br/>

[![My Skills](https://skillicons.dev/icons?i=python,pytorch,fastapi,docker,terraform,grafana,redis,postgres,githubactions&theme=dark)](https://skillicons.dev)

</div>

---

<h2 align="center">Команда ИИ-разработки TechCon</h2>

Machine Learning команда внутри [TechCon](https://techcon.ru) — компании, занимающейся цифровым обследованием зданий и сооружений. Мы проектируем, строим и сопровождаем весь технический стек: от исследований и моделей до инфраструктуры и продакшн-деплоя.

---

<h2 align="center">О компании</h2>

TechCon разрабатывает специализированную платформу для технических обследований зданий. Единственное в России ПО такого класса — автоматизирует сбор, анализ и визуализацию данных по объектам недвижимости.

<br/>

<div align="center">

| | |
|:---:|:---:|
| **25+ лет** опыта в обследовании зданий | **150+** клиентов и партнёров |
| **20 000+** объектов в системе | **в 4 раза** быстрее рыночного стандарта |

</div>

---

<h2 align="center">Что мы разрабатываем</h2>

Собственный стек ML-инструментов и сервисов для платформы цифрового обследования:

**Инструменты инспекции**
- **Распознавание паспортов** — PDF и фото оборудования в структурированные данные (FastAPI + Celery + PostgreSQL, production)
- **Классификация дефектов по голосу** — полевые обходы без бумажных бланков (GigaAM STT + классификатор на GPU, production)
- **Визуальная дефектоскопия** — автоматическое выявление дефектов по фото (DINOv3 + MLflow на A100, production)
- **Поиск технических планов** — атрибутный и семантический поиск по базе объектов (FastAPI + Redis, production)

**Инфраструктура и платформа**
- **Автоскейлинг GPU-кластера** — burst VM поднимаются автоматически при росте очереди задач, управляются через Yandex Cloud API
- **Observability stack** — 24-сервисный мониторинг: Grafana + VictoriaMetrics + Loki + Alertmanager

**В разработке**
- **Обучение сотрудников** — RAG-чатбот на базе регламентных документов (FastAPI + Celery + pgvector + OpenRouter)
- **Валидатор отчётов МКД** — автоматическая проверка PDF по ГОСТ 31937-2024 (rule engine, 53 правила)

<br/>

![Activity Graph](https://techcon-activity-graph.vercel.app/graph?custom_title=TechCon-ML-Team&bg_color=0d1117&color=8E8699&line=4A4453&point=F1F5F2&area=true&hide_border=true)

---

<h2 align="center">Как мы работаем</h2>

<div align="center">
Несколько принципов, которые определяют инженерную культуру команды.
</div>

<br/>

**От разработки сразу в работу.** Инструменты создаются для реального использования — каждый сервис деплоится, покрыт тестами и мониторится. Прототипы не живут долго: если что-то полезно, оно становится полноценным сервисом.

**Наблюдаемость с первого дня.** Каждый сервис получает `/health`, Gatus healthcheck, Grafana дашборд и alert rules до выхода в production. Мониторинг — часть определения "сделано", а не отдельный этап после.

**Общий API-стандарт.** Все HTTP-сервисы следуют единой методологии: Bearer JWT аутентификация, версионированные URL (`/api/v1/`), стандартный response envelope, машиночитаемые error codes. Решения принимаются один раз и применяются последовательно.

**Безопасность по умолчанию.** GitHub Actions refs закреплены на SHA, `.env` gitignored во всех репозиториях, middleware с allowlist-моделью — доступ открывается явно, а не закрывается постфактум. Секреты только через переменные окружения.

**Инфраструктура как код.** Каждое изменение в облаке проходит через Terraform. Образы VM — через Packer, ротация без downtime. Ручные изменения в облаке не приветствуются — они не воспроизводимы и не ревьюируются.

**Централизованное знание.** Внутренний knowledge hub автоматически отслеживает состояние всех репозиториев: CI-статус, последние изменения, архитектурный дрейф. При каждом push в любой репозиторий — автосинк.

---

<h2 align="center">Демо</h2>

<div align="center">

Попробуйте наши инструменты в работе — три интерактивных стенда:

<br/>

[![Открыть демо](https://img.shields.io/badge/открыть_демо-pyramidheadshark--techcon--demos.ru.tuna.am-4A4453?style=for-the-badge&logo=streamlit&logoColor=F1F5F2&labelColor=625B6D)](https://pyramidheadshark-techcon-demos.ru.tuna.am)

</div>

---

<h2 align="center">Контакты</h2>

<div align="center">

[![Сайт](https://img.shields.io/badge/techcon.ru-4A4453?style=flat-square&labelColor=625B6D)](https://techcon.ru)&nbsp;&nbsp;
[![Telegram](https://img.shields.io/badge/techcon__ai-4A4453?style=flat-square&logo=telegram&logoColor=F1F5F2&labelColor=625B6D)](https://t.me/techcon_ai)&nbsp;&nbsp;
[![VK](https://img.shields.io/badge/techcon__ai-4A4453?style=flat-square&logo=vk&logoColor=F1F5F2&labelColor=625B6D)](https://vk.com/techcon_ai)

</div>

---

<div align="center">
<br/>

[![techcon.ru](https://img.shields.io/badge/techcon.ru-625B6D?style=for-the-badge)](https://techcon.ru)

</div>

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=18&pause=2000&color=8E8699&background=0D111700&center=true&vCenter=true&width=600&lines=ML-инжиниринг+для+промышленной+инспекции;R%26D+%C2%B7+Разработка+%C2%B7+Продакшн+%C2%B7+MLOps;Речь+%C2%B7+Зрение+%C2%B7+Документы+%C2%B7+Инфраструктура)](https://git.io/typing-svg)

<br/>

[![My Skills](https://skillicons.dev/icons?i=python,pytorch,fastapi,docker,terraform,grafana,redis,postgres,githubactions&theme=dark)](https://skillicons.dev)

</div>

---

<h2 align="center">О команде</h2>

Самостоятельный отдел разработки в TechCon. Занимаемся полным циклом —
от исследований до промышленного запуска, включая сопровождение и инфраструктуру.

---

<h2 align="center">Сервисы</h2>

<table>
  <tr>
    <td><b>techcon_passports</b></td>
    <td>Распознавание паспортов: PDF/фото → структурированные данные</td>
    <td><img src="https://img.shields.io/badge/status-production-2d6a4f?style=flat-square&labelColor=4A4453"/></td>
  </tr>
  <tr>
    <td><b>techcon_defects_stt_plus</b></td>
    <td>Голосовые записи дефектов → классификация по таксономии SP-547</td>
    <td><img src="https://img.shields.io/badge/status-phase_R6-6b4226?style=flat-square&labelColor=4A4453"/></td>
  </tr>
  <tr>
    <td><b>techcon_defectoscopy</b></td>
    <td>Визуальная дефектоскопия на нейросетевых признаках (DINOv3)</td>
    <td><img src="https://img.shields.io/badge/status-phase_1-6b4226?style=flat-square&labelColor=4A4453"/></td>
  </tr>
  <tr>
    <td><b>techcon_techplans_search</b></td>
    <td>Поиск технических планов по атрибутам</td>
    <td><img src="https://img.shields.io/badge/status-stable-1a5276?style=flat-square&labelColor=4A4453"/></td>
  </tr>
  <tr>
    <td><b>techcon_demos</b></td>
    <td>Демонстрационные стенды всех продуктов</td>
    <td><img src="https://img.shields.io/badge/status-production-2d6a4f?style=flat-square&labelColor=4A4453"/></td>
  </tr>
</table>

---

<h2 align="center">Инфраструктура</h2>

Облачная платформа на базе Yandex Cloud:

- **Контроллер-нод** — постоянно активен, обслуживает все сервисы
- **GPU-воркеры** — A100 и V100, запускаются по требованию, автоматически останавливаются после простоя
- **CPU-воркеры** — задачи без GPU-ускорения
- **Объектное хранилище** — датасеты и веса моделей

Инфраструктура описана декларативно через Terraform, образы — через Packer.
Наблюдаемость: VictoriaMetrics + Grafana + Loki + Alertmanager.

---

<h2 align="center">Принципы разработки</h2>

**Единая экосистема** — компоненты спроектированы как части платформы цифрового обследования.
Каждый сервис знает своё место и интерфейс взаимодействия.

**Единые стандарты** — общий каркас, единое CI, конвенции оформления кода.
Новый сервис встраивается в инфраструктуру за часы, не недели.

**Наблюдаемость с первого дня** — логи, метрики, отслеживание ошибок и автоматические тесты
закладываются в сервис с начала разработки, а не добавляются после.

**Переносимость** — минимум привязки к конкретному провайдеру, конфигурация через
переменные окружения, вся инфраструктура описана кодом. Обновляем компонент — не переписываем систему.

**Живая документация** — знания об архитектуре, решениях и стеке хранятся в репозиториях.
`techcon_hub` автоматически синхронизирует документацию по всей экосистеме.

---

<div align="center">
<br/>

[![techcon.ru](https://img.shields.io/badge/techcon.ru-625B6D?style=for-the-badge)](https://techcon.ru)

</div>

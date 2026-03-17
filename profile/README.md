<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=18&pause=2000&color=8E8699&background=0D111700&center=true&vCenter=true&width=600&lines=ML-инжиниринг+для+промышленной+инспекции;R%26D+%C2%B7+Разработка+%C2%B7+Продакшн+%C2%B7+MLOps;Речь+%C2%B7+Зрение+%C2%B7+Документы+%C2%B7+Инфраструктура)](https://git.io/typing-svg)

<br/>

[![My Skills](https://skillicons.dev/icons?i=python,pytorch,fastapi,docker,terraform,grafana,redis,postgres,githubactions&theme=dark)](https://skillicons.dev)

</div>

<img src="assets/divider.svg" width="100%"/>

## О команде

Самостоятельный отдел разработки в TechCon. Занимаемся полным циклом —
от исследований до промышленного запуска, включая сопровождение и инфраструктуру.

<img src="assets/divider.svg" width="100%"/>

## Сервисы

<table>
  <tr>
    <td><b>techcon_passports</b></td>
    <td>Распознавание паспортов: PDF/фото → структурированные данные</td>
    <td><img src="https://img.shields.io/badge/production-готов-4A4453?style=flat-square&labelColor=4A4453&color=2d6a4f"/></td>
  </tr>
  <tr>
    <td><b>techcon_defects_stt_plus</b></td>
    <td>Голосовые записи дефектов → классификация по таксономии SP-547</td>
    <td><img src="https://img.shields.io/badge/phase-R6-4A4453?style=flat-square&labelColor=4A4453&color=6b4226"/></td>
  </tr>
  <tr>
    <td><b>techcon_defectoscopy</b></td>
    <td>Визуальная дефектоскопия на нейросетевых признаках (DINOv3)</td>
    <td><img src="https://img.shields.io/badge/phase-1_завершён-4A4453?style=flat-square&labelColor=4A4453&color=6b4226"/></td>
  </tr>
  <tr>
    <td><b>techcon_techplans_search</b></td>
    <td>Поиск технических планов по атрибутам</td>
    <td><img src="https://img.shields.io/badge/feature-complete-4A4453?style=flat-square&labelColor=4A4453&color=1b4332"/></td>
  </tr>
  <tr>
    <td><b>techcon_demos</b></td>
    <td>Демонстрационные стенды всех продуктов</td>
    <td><img src="https://img.shields.io/badge/production-готов-4A4453?style=flat-square&labelColor=4A4453&color=2d6a4f"/></td>
  </tr>
</table>

<img src="assets/divider.svg" width="100%"/>

## Инфраструктура

Облачная платформа на базе Yandex Cloud:

- **Узел-контроллер** — 4 ЦП / 16 ГБ ОЗУ / 512 ГБ SSD, всегда активен
- **GPU-воркеры** — A100 80 ГБ (28 ЦП / 119 ГБ) и V100 32 ГБ (8 ЦП / 96 ГБ) — запускаются по требованию, автоматически останавливаются после 4 часов простоя
- **CPU-воркеры** — 4 ЦП / 16 ГБ, типовые конфигурации для задач без ускорителей
- **Хранилище** — объектное хранилище YC (наборы данных, веса моделей)

Парк узлов описан декларативно через Terraform; образы собираются через Packer.
Наблюдаемость: VictoriaMetrics + Grafana + Loki + Alertmanager.

<img src="assets/divider.svg" width="100%"/>

## Принципы разработки

**Единая экосистема** — компоненты спроектированы как части платформы цифрового обследования.
Каждый сервис знает своё место и интерфейс взаимодействия.

**Единые стандарты** — общий каркас, единое CI, конвенции оформления кода.
Новый сервис встраивается в инфраструктуру за часы, не недели.

**Готовность к продакшну с первого дня** — наблюдаемость, отслеживание ошибок, проверки
работоспособности и автоматические тесты закладываются с начала, а не добавляются потом.

**Переносимость** — минимум привязки к конкретному провайдеру, конфигурация через
переменные окружения, вся инфраструктура описана кодом. Обновляем компонент — не переписываем систему.

**Живая документация** — знания об архитектуре, решениях и стеке хранятся в репозиториях.
`techcon_hub` автоматически синхронизирует документацию по всей экосистеме.

<img src="assets/divider.svg" width="100%"/>

<div align="center">

[techcon.pro](https://techcon.pro)

</div>

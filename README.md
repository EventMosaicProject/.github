# 🌍 Event Mosaic — система агрегации и анализа данных GDELT

## 🔍 О проекте
**Event Mosaic** — это микросервисная система для сбора, обработки и анализа данных. Проект построен на основе **GDELT**.  

🔗 **Все репозитории проекта находятся в этой организации.**  

---

## ⚙️ Архитектура и ключевые компоненты

![Event Mosaic Project](https://github.com/user-attachments/assets/d35cf53e-8ab1-41c4-a4a4-8795ed29b589)

| Репозиторий        | Описание                                      |
|--------------------|----------------------------------------------|
| [docker](https://github.com/EventMosaicProject/docker) | **Docker-конфигурации** для развертывания всех микросервисов. |
| [em-adapter](https://github.com/EventMosaicProject/em-adapter) | **Адаптеры** для интеграции с внешними системами. |
| [em-gateway](https://github.com/EventMosaicProject/em-gateway) | **API-шлюз**, обеспечивающий маршрутизацию и безопасность. |
| [em-collector](https://github.com/EventMosaicProject/em-collector) | **Сбор данных** из различных источников. |
| [em-processor](https://github.com/EventMosaicProject/em-processor) | **Обработка данных** и их структурирование. |
| [em-api](https://github.com/EventMosaicProject/em-api) | **Внешний API** для работы с обработанными данными. |
| [em-discovery](https://github.com/EventMosaicProject/em-discovery) | **Service Discovery** для управления микросервисами. |

---

## 🛠 Как развернуть проект?
```bash
# 1. Клонируем репозиторий конфигурации
git clone https://github.com/EventMosaicProject/docker.git

# 2. Переходим в каталог
cd docker

# 3. Запускаем систему
docker compose -f compose.dev.yml up -d
```
🔹 **Требования**: установленный `Docker` и `Docker Compose`.  


<div align="center">

<img src="https://raw.githubusercontent.com/Buckley27/MBzeGuard/main/assets/logo.png" alt="MBzeGuard Logo" width="120" height="120" />

# MBzeGuard

**Современный прокси-клиент для Windows и Android**

*На основе [Mihomo (Clash.Meta)](https://github.com/MetaCubeX/mihomo)*

[![Windows](https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white)](https://github.com/Buckley27/MBzeGuard/releases)
[![Android](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)](https://github.com/Buckley27/MBzeGuard/releases)
[![GitHub Releases](https://img.shields.io/github/v/release/Buckley27/MBzeGuard?style=for-the-badge&color=blueviolet)](https://github.com/Buckley27/MBzeGuard/releases)
[![License](https://img.shields.io/github/license/Buckley27/MBzeGuard?style=for-the-badge)](LICENSE)

---

</div>

## 📖 О проекте

**MBzeGuard** — это форк [Hiddify](https://github.com/hiddify/hiddify-app) с глубокой интеграцией [Remnawave](https://github.com/remnawave) и расширенным набором возможностей для конечных пользователей.

Переработанный интерфейс, русская локализация, умные уведомления и нативная поддержка HWID-аутентификации делают MBzeGuard идеальным выбором для провайдеров VPN-услуг и их клиентов.

---

## ✨ Возможности

### 🔗 Интеграция с Remnawave
| Функция | Описание |
|---|---|
| **HWID-аутентификация** | Привязка к уникальному ID устройства |
| **Автообновление профилей** | По расписанию, заданному в панели провайдера |
| **Support link** | Прямая ссылка на поддержку вашего провайдера |
| **Announce** | Важные сообщения от провайдера прямо в приложении |

### 🔔 Умные уведомления

- **Трафик:** предупреждения при достижении 80% / 90% / 100% лимита
- **Подписка:** напоминания об истечении за 7, 3 и 1 день
- Настройка через HTTP-заголовки (base64)

### ⚙️ Гибкая настройка

- **Быстрый старт** — преднастроенные параметры без сложной конфигурации
- **Оверайд ядра** — переопределение параметров (`log-level`, `ipv6`, `mixed-port` и др.) прямо из конфига подписки
- **TUN-режим** на Windows через системный сервис

### 🎨 Интерфейс

- Полная **русская локализация**
- **Виджет подписки** на главном экране — трафик, дата истечения, статус
- **Тёмная и светлая** темы
- Полностью переработанный **UI/UX** относительно оригинального Clash

---

## 🚀 Установка

Скачай готовую сборку со страницы **[Releases](https://github.com/Buckley27/MBzeGuard/releases)**:

| Платформа | Файл |
|---|---|
| 🪟 **Windows** | `MBzeGuard-Setup-*.exe` |
| 🤖 **Android** | `MBzeGuard-*.apk` |

> [!NOTE]
> На Android может потребоваться разрешить установку из неизвестных источников.

> [!NOTE]
> На Windows установщик создаст системный сервис для TUN-режима. Требуются права администратора.

---

## 🛠️ Сборка из исходников

```bash
# Клонировать репозиторий
git clone https://github.com/Buckley27/MBzeGuard.git
cd MBzeGuard

# Установить зависимости
flutter pub get

# Сборка для Windows
flutter build windows

# Сборка для Android
flutter build apk
```

> Убедись, что у тебя установлен [Flutter SDK](https://flutter.dev/docs/get-started/install).

---

## 🤝 Участие в разработке

Pull request'ы приветствуются! Для крупных изменений сначала открой issue для обсуждения.

1. Форкни репозиторий
2. Создай ветку (`git checkout -b feature/amazing-feature`)
3. Закоммить изменения (`git commit -m 'Add amazing feature'`)
4. Запушь ветку (`git push origin feature/amazing-feature`)
5. Открой Pull Request

---

## 📄 Лицензия

Распространяется под лицензией **GPL-3.0**. Подробнее — в файле [LICENSE](LICENSE).

---

<div align="center">

Сделано с ❤️ на основе [Mihomo](https://github.com/MetaCubeX/mihomo) и [Hiddify](https://github.com/hiddify/hiddify-app)

</div>

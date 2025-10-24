<div align="center">

# 👋 Привет! Рахман здесь

**C++ Developer | Systems Programming Enthusiast | Open Source Contributor**

*Делаю невозможное вознеможным*

[![GitHub followers](https://img.shields.io/github/followers/RakhmaMed?style=social)](https://github.com/RakhmaMed)
[![GitHub stars](https://img.shields.io/github/stars/RakhmaMed?style=social)](https://github.com/RakhmaMed)

</div>

---

## 🚀 О себе

Увлекаюсь системным программированием, сетевыми протоколами и созданием эффективных инструментов для разработчиков. Специализируюсь на **C/C++**, работе с низкоуровневыми API и построении высокопроизводительных систем.

> 💡 *"Пишу код, который работает близко к железу, но остаётся понятным для людей"*

---

## 🛠️ Технологический стек

```cpp
const auto skills = {
    "Languages":   ["C++20/17/14", "C", "Modern C++"],
    "Async":       ["Boost.Asio", "Actor Pattern", "Coroutines"],
    "Networking":  ["TCP/IP", "HTTP/RTSP", "PCAP Analysis"],
    "Tools":       ["CMake", "vcpkg", "GDB", "Wireshark"],
    "Patterns":    ["Zero-Copy", "Header-Only", "RAII", "Type-Safe APIs"]
};
```

---

## 📦 Мои проекты

### 🔍 [PatternSeeker](https://github.com/RakhmaMed/PatternSeeker)
> Легковесная header-only библиотека для эффективного парсинга строк

**Особенности:**
- ⚡ Абстракция с нулевой стоимостью через `std::string_view`
- 🎯 Поддержка JSON и XML из коробки
- 🔧 Header-only, без внешних зависимостей
- 📚 Типобезопасный парсинг с обработкой ошибок

```cpp
PatternSeeker json(R"({"name": "Alice", "score": 42})");
auto name = json.getJsonProp("name");  // "Alice"
auto score = json.getJsonProp("score").takeUInt64();  // 42
```

**Tech Stack:** `C++20` `std::string_view` `Zero-Copy Design` `CMake`

---

### 🔍 [PcapParser](https://github.com/RakhmaMed/PcapParserVcpg)
> Мощный инструмент для анализа сетевого трафика и эмуляции устройств

**Возможности:**
- 📡 Полный парсинг PCAP файлов с реассемблированием TCP
- 🎭 Эмуляция HTTP/RTSP серверов на основе захваченного трафика
- 🔄 Асинхронная архитектура с Boost.Asio
- 🛠️ Утилиты для извлечения HTTP транзакций и медиа-потоков

**Применение:** Тестирование клиентов, отладка протоколов, анализ безопасности

**Tech Stack:** `C++20` `Boost.Asio` `vcpkg` `TCP Reassembly` `HTTP/RTSP`

---

### 🚀 [http11](https://github.com/RakhmaMed/http11)
> Экспериментальный HTTP/1.1 клиент с собственной реализацией Actor-based async pattern

**Ключевые идеи:**
- 🎯 Линейный код в асинхронном виде через pipeline operators
- 🔧 Работа со старыми стандартами (C++14, Boost 1.68)
- ⚙️ Собственный Actor Framework для композиции операций
- 📝 Избавление от "callback hell"

```cpp
createService(state)
    | async(connect)
    | filter(check_error)
    | async(write_request)
    | async(read_response)
    | sink(handle_response)
    .start();
```

**Tech Stack:** `C++14` `Boost.Beast` `Boost.Asio` `Actor Pattern` `Pipeline Operators`

---

### 🪶 [Pero](https://github.com/RakhmaMed/pero)
> Легковесный текстовый редактор для терминала

**Фичи:**
- 📝 Подсветка синтаксиса и инкрементальный поиск
- ⌨️ Интуитивная навигация и горячие клавиши
- 🎓 Учебный проект: демонстрация работы терминала в raw-режиме
- 💻 Работа с ANSI escape-последовательностями

**Идеален для:** Понимания низкоуровневой работы терминала и текстовых редакторов

**Tech Stack:** `Pure C` `POSIX` `Terminal Programming` `Raw Mode`

---

## 📊 GitHub статистика

<div align="center">

![RakhmaMed's GitHub stats](https://github-readme-stats.vercel.app/api?username=RakhmaMed&show_icons=true&theme=tokyonight)

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=RakhmaMed&layout=compact&theme=tokyonight)

</div>

---

## 🎯 Области интересов

- 🔌 **Системное программирование** — работа с низкоуровневыми API и оптимизация производительности
- 🌐 **Сетевые протоколы** — TCP/IP, HTTP, RTSP, анализ и эмуляция трафика
- ⚡ **Асинхронное программирование** — современные паттерны для высокопроизводительных систем
- 📚 **Библиотеки и инструменты** — создание переиспользуемого кода для разработчиков
- 🎓 **Образовательные проекты** — демонстрация концепций и лучших практик

---

## 🌟 Философия разработки

```cpp
class MyApproach {
public:
    // Простота важнее сложности
    void keepItSimple() { /* KISS principle */ }

    // Производительность по умолчанию
    [[nodiscard]] auto zeroOverhead() const noexcept { /* Zero-cost abstractions */ }

    // Читаемый код = поддерживаемый код
    auto makeItReadable() { /* Self-documenting code */ }

    // Обучение через практику
    void learnByDoing() { /* Educational projects */ }
};
```

---

## 📫 Связь

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-RakhmaMed-181717?style=for-the-badge&logo=github)](https://github.com/RakhmaMed)
[![Email](https://img.shields.io/badge/Email-Contact-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:irahman5000@gmail.com)

</div>

---

## 💡 Интересные факты

- 🔧 Предпочитаю писать код, который компилируется с первого раза
- 📖 Верю в силу хороших комментариев и подробной документации
- ⚡ Фанат zero-copy дизайна и RAII паттерна
- 🎯 Люблю экспериментировать с нестандартными подходами к решению задач

---

<div align="center">

### ⭐ Если мои проекты оказались полезными — поставьте звёздочку!

**Made with ❤️ and C++**

![Profile views](https://komarev.com/ghpvc/?username=RakhmaMed&color=blueviolet&style=flat-square)

</div>

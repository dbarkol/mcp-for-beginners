<!--
CO_OP_TRANSLATOR_METADATA:
{
  "original_hash": "97f1c99b5b12cf03d4b1be68b3636a4a",
  "translation_date": "2025-07-04T19:27:46+00:00",
  "source_file": "03-GettingStarted/README.md",
  "language_code": "uk"
}
-->
## Початок роботи  

Цей розділ складається з кількох уроків:

- **1 Ваш перший сервер**, у цьому першому уроці ви навчитеся створювати свій перший сервер та перевіряти його за допомогою інструменту інспектора — корисного способу тестування та налагодження сервера, [до уроку](/03-GettingStarted/01-first-server/README.md)

- **2 Клієнт**, у цьому уроці ви дізнаєтеся, як написати клієнта, який може підключатися до вашого сервера, [до уроку](/03-GettingStarted/02-client/README.md)

- **3 Клієнт з LLM**, ще кращий спосіб написання клієнта — додати до нього LLM, щоб він міг "узгоджувати" з вашим сервером, що робити, [до уроку](/03-GettingStarted/03-llm-client/README.md)

- **4 Використання режиму агента GitHub Copilot сервера в Visual Studio Code**. Тут ми розглядаємо запуск нашого MCP Server безпосередньо у Visual Studio Code, [до уроку](/03-GettingStarted/04-vscode/README.md)

- **5 Використання SSE (Server Sent Events)** SSE — це стандарт для потокової передачі від сервера до клієнта, що дозволяє серверам надсилати оновлення в реальному часі клієнтам через HTTP [до уроку](/03-GettingStarted/05-sse-server/README.md)

- **6 HTTP-потокова передача з MCP (Streamable HTTP)**. Дізнайтеся про сучасну HTTP-потокову передачу, сповіщення про прогрес і як реалізувати масштабовані сервери та клієнти MCP у реальному часі за допомогою Streamable HTTP. [до уроку](/03-GettingStarted/06-http-streaming/README.md)

- **7 Використання AI Toolkit для VSCode** для споживання та тестування ваших MCP клієнтів і серверів [до уроку](/03-GettingStarted/07-aitk/README.md)

- **8 Тестування**. Тут ми зосередимося на різних способах тестування нашого сервера та клієнта, [до уроку](/03-GettingStarted/08-testing/README.md)

- **9 Розгортання**. Цей розділ розгляне різні способи розгортання ваших MCP-рішень, [до уроку](/03-GettingStarted/09-deployment/README.md)


Model Context Protocol (MCP) — це відкритий протокол, який стандартизує спосіб надання контексту LLM додатками. Уявіть MCP як порт USB-C для AI-додатків — він забезпечує стандартизований спосіб підключення AI-моделей до різних джерел даних і інструментів.

## Цілі навчання

Після завершення цього уроку ви зможете:

- Налаштувати середовища розробки для MCP на C#, Java, Python, TypeScript та JavaScript
- Створювати та розгортати базові MCP сервери з користувацькими функціями (ресурси, підказки та інструменти)
- Створювати хост-додатки, які підключаються до MCP серверів
- Тестувати та налагоджувати реалізації MCP
- Розуміти типові проблеми налаштування та їх вирішення
- Підключати ваші реалізації MCP до популярних LLM сервісів

## Налаштування середовища MCP

Перед тим, як почати працювати з MCP, важливо підготувати середовище розробки та зрозуміти базовий робочий процес. Цей розділ проведе вас через початкові кроки налаштування, щоб забезпечити плавний старт з MCP.

### Вимоги

Перед тим, як зануритися у розробку MCP, переконайтеся, що у вас є:

- **Середовище розробки**: для обраної мови (C#, Java, Python, TypeScript або JavaScript)
- **IDE/редактор**: Visual Studio, Visual Studio Code, IntelliJ, Eclipse, PyCharm або будь-який сучасний редактор коду
- **Менеджери пакетів**: NuGet, Maven/Gradle, pip або npm/yarn
- **API ключі**: для будь-яких AI-сервісів, які ви плануєте використовувати у своїх хост-додатках


### Офіційні SDK

У наступних розділах ви побачите рішення, створені з використанням Python, TypeScript, Java та .NET. Ось усі офіційно підтримувані SDK.

MCP надає офіційні SDK для кількох мов:
- [C# SDK](https://github.com/modelcontextprotocol/csharp-sdk) — підтримується у співпраці з Microsoft
- [Java SDK](https://github.com/modelcontextprotocol/java-sdk) — підтримується у співпраці з Spring AI
- [TypeScript SDK](https://github.com/modelcontextprotocol/typescript-sdk) — офіційна реалізація на TypeScript
- [Python SDK](https://github.com/modelcontextprotocol/python-sdk) — офіційна реалізація на Python
- [Kotlin SDK](https://github.com/modelcontextprotocol/kotlin-sdk) — офіційна реалізація на Kotlin
- [Swift SDK](https://github.com/modelcontextprotocol/swift-sdk) — підтримується у співпраці з Loopwork AI
- [Rust SDK](https://github.com/modelcontextprotocol/rust-sdk) — офіційна реалізація на Rust

## Основні висновки

- Налаштування середовища розробки MCP є простим завдяки SDK для конкретних мов
- Створення MCP серверів включає створення та реєстрацію інструментів з чіткими схемами
- MCP клієнти підключаються до серверів і моделей, щоб використовувати розширені можливості
- Тестування та налагодження є необхідними для надійних реалізацій MCP
- Варіанти розгортання варіюються від локальної розробки до хмарних рішень

## Практика

У нас є набір прикладів, які доповнюють вправи, що ви побачите у всіх розділах цього розділу. Крім того, кожен розділ має власні вправи та завдання.

- [Java калькулятор](./samples/java/calculator/README.md)
- [.Net калькулятор](../../../03-GettingStarted/samples/csharp)
- [JavaScript калькулятор](./samples/javascript/README.md)
- [TypeScript калькулятор](./samples/typescript/README.md)
- [Python калькулятор](../../../03-GettingStarted/samples/python)

## Додаткові ресурси

- [Створення агентів за допомогою Model Context Protocol на Azure](https://learn.microsoft.com/azure/developer/ai/intro-agents-mcp)
- [Віддалений MCP з Azure Container Apps (Node.js/TypeScript/JavaScript)](https://learn.microsoft.com/samples/azure-samples/mcp-container-ts/mcp-container-ts/)
- [.NET OpenAI MCP Agent](https://learn.microsoft.com/samples/azure-samples/openai-mcp-agent-dotnet/openai-mcp-agent-dotnet/)

## Що далі

Далі: [Створення вашого першого MCP сервера](./01-first-server/README.md)

**Відмова від відповідальності**:  
Цей документ було перекладено за допомогою сервісу автоматичного перекладу [Co-op Translator](https://github.com/Azure/co-op-translator). Хоча ми прагнемо до точності, будь ласка, майте на увазі, що автоматичні переклади можуть містити помилки або неточності. Оригінальний документ рідною мовою слід вважати авторитетним джерелом. Для критично важливої інформації рекомендується звертатися до професійного людського перекладу. Ми не несемо відповідальності за будь-які непорозуміння або неправильні тлумачення, що виникли внаслідок використання цього перекладу.
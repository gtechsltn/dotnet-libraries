# What are your favorites nuget package, libraries or tools for use with .NET?
+ https://www.reddit.com/r/dotnet/comments/1gyisc0/what_are_your_favorites_nuget_package_libraries/

# .NET Libraries
+ Polly
+ MassTransit
+ Scrutor
+ Humanizer
+ FluentAutomation
+ FluentEmail
+ FluentValidation
+ FluentMigrator
+ FluentResults
+ FluentAssertions
+ xUnit
+ NUnit
+ Microsoft.EntityFrameworkCore
+ EntityFrameworkCore.Projectables
+ EFCore.BulkExtensions
+ Z.EntityFramework.Plus.EFCore
+ Validot
+ Mapster
+ GuardClasses
+ Rebus (about Event Bus)
+ Math.Statistics
+ Numerics
+ FreeSql
+ SqlSugar
+ SqlKata
+ Dapper
+ Dapper.Contrib
+ DapperExtensions
+ Dapper.SqlBuilder
+ Linq2DB
+ Newtonsoft.Json
+ Generic Host
+ Serilog
+ ASP.NET Core
+ Swashbuckle Swagger
+ RicoSuter NSwag
+ RicoSuter NSwagStudio
+ EF Core
+ Refit
+ RestSharp
+ Verify
+ FakeItEasy
+ AutoFixture
+ Moq
+ NSubstitute
+ Bogus
+ AutoMapper
+ Spectre Console
+ Dumpify
+ ServiceStack
+ ServiceStack.Common
+ ServiceStack.Text
+ FastMember
+ Autofac
+ HangFire
+ Quartz.NET
+ Coravel
+ MediatR
+ Confluent.Kafka
+ MailKit
+ IdentityServer4
+ SharpZipLib
+ CsvHelper
+ EPPlus
+ NPOI
+ iText
+ System.Text.Json
+ NodaTime
+ DateTimeExtensions
+ HtmlAgilityPack
+ AngleSharp
+ Microsoft.Extensions.Caching.Memory
+ Respawn
+ Coverlet
+ Selenium.WebDriver
+ Flurl
+ HttpClient
+ SignalR
+ System.CommandLine
+ DotMake.CommandLine
+ CommandLineParser
+ FakeHttpContext
+ WireMock.Net
+ FluentAssertions.Extensions
+ Microsoft.Playwright
+ YamlDotNet
+ DnsClient
+ BenchmarkDotNet
+ SharpZipLib
+ SharpCompress
+ RabbitMQ.Client
+ BouncyCastle.Cryptography
+ log4net
+ RandomDataGenerator.Net
+ Hangfire.Core
+ prometheus-net
+ System.Linq.Dynamic.Core
+ TimeZoneConverter
+ Mediator
+ MediatR
+ SSH.NET
+ EntityFrameworkCore.Exceptions.SqlServer
+ EFCore.Visualizer
+ JJMasterData (CRUD)
+ DateTimeToStringWithSuffix
+ StringTokenFormatter
+ RT.Comb
+ RT.Comb.AspNetCore
+ GemBox.Spreadsheet
+ X.PagedList
+ X.PagedList.Mvc.Core
+ X.PagedList.EF
+ X.Spectator
+ X.Web.MetaExtractor
+ X.Web.Sitemap
+ X.Extensions.Logging.Telegram
+ ZXing.NET
+ ScottPlot: Interactive plotting library for .NET
+ Testcontainers
+ DynamicData
+ ZenRows

## ZenRows
+ [HTML Agility Pack: How to Parse Data (Tutorial 2024)](https://www.zenrows.com/blog/html-agility-pack)
+ [7 Best C# Web Scraping Libraries in 2024](https://www.zenrows.com/blog/c-sharp-web-scraping-library)
+ [Web Crawler in C#: Step-by-Step Tutorial [2024]](https://www.zenrows.com/blog/c-sharp-web-crawler)

## List of Automated Testing (TDD/BDD/ATDD/SBE) Tools and Frameworks for .NET
https://github.com/dariusz-wozniak/List-of-Testing-Tools-and-Frameworks-for-.NET

## Clean Architecture

Clean Architecture is a software design philosophy introduced by Robert C. Martin (often referred to as Uncle Bob) that emphasizes the separation of concerns, maintainability, and testability of software systems. The architecture consists of concentric circles, where each circle represents a different layer in the application. The innermost layer consists of the core business logic and is unaffected by external factors, while the outer layers handle user interface, frameworks, and other external systems.

### Key Concepts of Clean Architecture:

##### Separation of Concerns: Different responsibilities are assigned to different layers, allowing for easier navigation, maintenance, and understanding.
##### Dependency Rule: Dependencies should only point inward; outer layers can depend on inner layers, but not vice versa. This means the core business logic is independent of frameworks, UI, and other external systems.
##### Independence: The architecture is independent of any specific technology, making it easier to change technologies without affecting the core business logic.
##### Testability: By isolating business rules from external concerns, it becomes easier to create automated tests for the core logic.

### Layers of Clean Architecture:

##### Entities: Core business rules and models.
##### Use Cases (or Interactors): Application-specific business rules relating to how entities are used.
##### Interface Adapters: Conversion of data, containing controllers and presenters to prepare data for presentation.
##### Frameworks and Drivers: External frameworks, UI, databases, and other external tools.

### Advantages of Clean Architecture:

##### Maintainability: The separation of interfaces and implementation makes it easier to update individual components without affecting others.
##### Testability: Business logic can be easily tested in isolation from other layers, promoting better unit test coverage.
##### Flexibility: Changes in technology (such as switching databases) can be made with minimal impact on the core business logic.
##### Scalability: The architecture can grow organically as the application evolves, accommodating new features without significant refactoring.
##### Improved Collaboration: Clear separation of layers can facilitate collaboration between teams focused on different aspects of the application (e.g., frontend vs. backend).

### Disadvantages of Clean Architecture:

##### Complexity: For small applications, the overhead of setting up multiple layers may be unnecessary and complicate the architecture.
##### Learning Curve: Developers unfamiliar with the concepts or principles may find it challenging to understand and implement clean architecture effectively.
##### Initial Overhead: Designing an application using Clean Architecture may require more upfront design effort and architectural thinking than simple implementations.
##### Performance Impact: While abstractions are beneficial for maintainability and scalability, they could introduce performance overhead due to indirection and extra layers of processing.
##### Over-engineering: There's a risk of over-engineering the architecture for small, trivial applications that do not require such a layered approach.

Clean Architecture is a powerful design principle that promotes the separation of concerns and encourages more maintainable and testable code. It is particularly beneficial for large and complex applications where the agility of changes and robustness of the system are crucial. However, it's essential to consider the requirements of the application, as it may introduce unnecessary complexity for simpler projects.

![Laravel Logo](https://raw.githubusercontent.com/fukuball/Awesome-Laravel-Education/master/laravel-logo-white.png)

# Awesome Laravel Education [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of resources for learning about the Laravel PHP Framework, there are [English Version](#user-content-english-version--英文版) and [Chinese Version](#user-content-chinese-version--中文版).

這是一個有關學習 Laravel PHP Framework 的資源列表，有 [英文版](#user-content-english-version--英文版) 及 [中文版](#user-content-chinese-version--中文版)。

# English Version / 英文版

## Index

- [New to Laravel](#user-content-new-to-laravel)
- [Quick References](#user-content-quick-references)
- [Learn From Video / Posts](#user-content-learn-from-video--posts)
  - [Composer / Homestead](#user-content-composer--homestead)
  - [Routing / Controllers / Requests / Responses](#user-content-routing--controllers--requests--responses)
  - [Database](#user-content-database)
  - [Models / Eloquent](#user-content-models--eloquent)
  - [Views / Blade](#user-content-views--blade)
  - [Forms / Validation](#user-content-forms--validation)
  - [Architecture Foundations / IoC](#user-content-architecture-foundations--ioc)
  - [Auth / Security](#user-content-auth--security)
  - [Middleware](#user-content-middleware)
  - [Front End](#user-content-front-end)
  - [Session](#user-content-session)
  - [Filesystem / Cloud Storage](#user-content-filesystem--cloud-storage)
  - [Cache](#user-content-cache)
  - [Mail](#user-content-mail)
  - [Testing and Coding Standard](#user-content-testing-and-coding-standard)
  - [Case Study](#user-content-case-study)
- [Tutorial](#user-content-tutorial)
- [Blogs](#user-content-blogs)
- [Newsletters](#user-content-newsletters)
- [Open Source Laravel](#user-content-open-source-laravel)
- [Coding Standard](#user-content-coding-standard)
- [Dependency Management](#user-content-dependency-management)
- [Develop Tools](#user-content-develop-tools)
- [PHP Book List for Developer](#user-content-php-book-list-for-developer)
- [Interview](#user-content-interview)

## New to Laravel

- [Laracasts: Laravel 5 Fundamentals](https://laracasts.com/series/laravel-5-fundamentals)
- Laravel 5.1 Homestead Install Guide
  - [Laravel Homestead on Windows 8](http://sherriflemings.blogspot.ca/2015/03/laravel-homestead-on-windows-8.html)
  - [Laravel Homestead on Linux or Mac](http://laravel.com/docs/5.1/homestead)
  - [Laracasts: Say Hello to Laravel Homestead 2.0](https://laracasts.com/lessons/say-hello-to-laravel-homestead-two)
- [Setup Laravel excutable enviroment on AWS EC2 quickly](https://github.com/fukuball/ec2-laravel-evn-installer)
- Learn from tutorial
  - [Laravel Documentation: Basic Task List](http://laravel.com/docs/5.1/quickstart)
  - [Laravel Documentation: Intermediate Task List](http://laravel.com/docs/5.1/quickstart-intermediate)
- [Laravel Documentation](http://laravel.com/docs/5.1)

## Quick References

- [Awesome Laravel](https://github.com/chiraggude/awesome-laravel)
- [Awesome PHP](https://github.com/ziadoz/awesome-php)
- [Laravel API](http://laravel.com/api/5.1/)

## Learn From Awesome Video / Posts

### Composer / Homestead

- Getting Started
  - [Laracasts: Meet Composer](https://laracasts.com/series/laravel-5-fundamentals/episodes/1) \#Composer
  - [Laracasts: Virtual Machines and Homestead](https://laracasts.com/series/laravel-5-fundamentals/episodes/2) \#Homestead \#Virtual Machine \#Vagrant
  - [Composer Intro](https://getcomposer.org/doc/00-intro.md)
  - [Laravel Documentation: Setup Homestead](http://laravel.com/docs/5.1/homestead) \#Homestead

### Routing / Controllers / Requests / Responses

- Getting Started
  - [Laracasts: A Gentle Introduction to Routing, Controllers, and Views](https://laracasts.com/series/laravel-5-fundamentals/episodes/3) \#Routing \#Controller \#View
  - [Laravel Documentation: The Basics Routing](http://laravel.com/docs/5.1/routing) \#Routing
  - [Laravel Documentation: The Basics Controllers](http://laravel.com/docs/5.1/controllers) \#Controller
  - [Laravel Documentation: The Basics Requests](http://laravel.com/docs/5.1/requests) \#Request
  - [Laravel Documentation: The Basics Responses](http://laravel.com/docs/5.1/responses) \#Response
- Advanced
  - [Laracasts: Route Model Binding](https://laracasts.com/series/laravel-5-fundamentals/episodes/18) \#Routing

### Database

- Getting Started
  - [Laracasts: Migrations](https://laracasts.com/series/laravel-5-fundamentals/episodes/7) \#Migration
  - [Laravel Documentation: Database Getting Started](http://laravel.com/docs/5.1/database) \#Database
  - [Laravel Documentation: Database Migrations](http://laravel.com/docs/5.1/migrations) \#Migration
- Advanced
  - [Laravel Documentation: Database Query Builder](http://laravel.com/docs/5.1/queries) \#Database
  - [Laravel Documentation: Database Seeding](http://laravel.com/docs/5.1/seeding) \#Migration

### Models / Eloquent

- Getting Started
  - [Laracasts: Eloquent 101](https://laracasts.com/series/laravel-5-fundamentals/episodes/8) \#Eloquent
  - [Laracasts: Basic Model/Controller/View Workflow](https://laracasts.com/series/laravel-5-fundamentals/episodes/9) \#Model \#Eloquent
  - [Laravel Documentation: Eloquent ORM Getting Started](http://laravel.com/docs/5.1/eloquent) \#Eloquent
- Advanced
  - [Laravel Documentation: Eloquent ORM Relationships](http://laravel.com/docs/5.1/eloquent-relationships) \#Eloquent
  - [Laravel Documentation: Eloquent ORM Collections](http://laravel.com/docs/5.1/eloquent-collections) \#Eloquent
  - [Laravel Documentation: Eloquent ORM Mutators](http://laravel.com/docs/5.1/eloquent-mutators) \#Eloquent
  - [Laravel Documentation: Eloquent ORM Serialization](http://laravel.com/docs/5.1/eloquent-serialization) \#Eloquent
  - [Laracasts: Dates, Mutators, and Scopes](https://laracasts.com/series/laravel-5-fundamentals/episodes/11) \#Eloquent \#Carbon
  - [Laracasts: Eloquent Relationships](https://laracasts.com/series/laravel-5-fundamentals/episodes/14) \#Eloquent

### Views / Blade

- Getting Started
  - [Laracasts: Passing Data to Views](https://laracasts.com/series/laravel-5-fundamentals/episodes/4) \#View
  - [Laravel Documentation: The Basics Views](http://laravel.com/docs/5.1/views) \#View
  - [Laracasts: Blade 101](https://laracasts.com/series/laravel-5-fundamentals/episodes/5) \#View \#Blade
  - [Laravel Documentation: The Basics Blade Templates](http://laravel.com/docs/5.1/blade) \#View \#Blade
- Advanced
  - [Laracasts: View Partials and Form Reuse](https://laracasts.com/series/laravel-5-fundamentals/episodes/13) \#View

### Forms / Validation

- Getting Started
  - [Laracasts: Forms](https://laracasts.com/series/laravel-5-fundamentals/episodes/10) \#Form \#View
  - [Laracasts: Form Requests and Controller Validation](https://laracasts.com/series/laravel-5-fundamentals/episodes/12) \#Form \#Validation
  - [Laravel Documentation: Services Validation](http://laravel.com/docs/5.1/validation) \#Validation

### Architecture Foundations / IoC

- Getting Started
  - [Laracasts: Environments and Configuration](https://laracasts.com/series/laravel-5-fundamentals/episodes/6) \#Architecture
  - [Laravel Documentation: Architecture Foundations Application Structure](http://laravel.com/docs/5.1/structure) \#Architecture
- Advanced
  - [Laravel Documentation: Architecture Foundations Request Lifecycle](http://laravel.com/docs/5.1/lifecycle) \#Architecture
  - [Laravel Documentation: Architecture Foundations Service Providers](http://laravel.com/docs/5.1/providers) \#Architecture
  - [Laravel Documentation: Architecture Foundations Service Container](http://laravel.com/docs/5.1/container) \#Architecture
  - [Laravel Documentation: Architecture Foundations Contracts](http://laravel.com/docs/5.1/contracts) \#Architecture
  - [Laravel Documentation: Architecture Foundations Facades](http://laravel.com/docs/5.1/facades) \#Architecture
  - [Laracasts: The Service Container](https://laracasts.com/series/laravel-5-fundamentals/episodes/26) \#Architecture \#Ioc

### Auth / Security

- Getting Started
  - [Laracasts: Easy Auth](https://laracasts.com/series/laravel-5-fundamentals/episodes/15) \#Authentication \#Eloquent
  - [Laravel Documentation: Services Authentication](http://laravel.com/docs/5.1/authentication) \#Authentication
  - [Laravel Documentation: Services Authorization](http://laravel.com/docs/5.1/authorization) \#Authentication

### Middleware

- Getting Started
  - [Laracasts: Ogres Are Like Middleware](https://laracasts.com/series/laravel-5-fundamentals/episodes/16) \#Middleware \#Security
  - [Laravel Documentation: The Basics Middleware](http://laravel.com/docs/5.1/middleware) \#Middleware

### Front End

- Getting Started
  - [Laracasts: Manage Your Assets](https://laracasts.com/series/laravel-5-fundamentals/episodes/19) \#Front End \#Elixir
  - [Laravel Documentation: Services Elixir](http://laravel.com/docs/5.1/elixir) \#Elixir

### Session

- Getting Started
  - [Laracasts: Flash Messaging](https://laracasts.com/series/laravel-5-fundamentals/episodes/20) \#Session
  - [Laravel Documentation: Services Session](http://laravel.com/docs/5.1/session) \#Session

### Filesystem / Cloud Storage

- Getting Started
  - [Laravel Documentation: Services Filesystem / Cloud Storage](http://laravel.com/docs/5.1/filesystem) \#Filesystem

### Cache

- Getting Started
  - [Laravel Documentation: Services Cache](http://laravel.com/docs/5.1/cache) \#Cache

### Mail

- Getting Started
  - [Laravel Documentation: Services Mail](http://laravel.com/docs/5.1/mail) \#Mail

### Testing and Coding Standard

- Getting Started
  - [Laravel Documentation: Services Testing](http://laravel.com/docs/5.1/testing) \#Testing

### Case Study

- Advanced
  - Article and Tags
    - [Laracasts: Many to Many Relations (With Tags)](https://laracasts.com/series/laravel-5-fundamentals/episodes/21) \#Eloquent
    - [Laracasts: Selecting Tags From the UI](https://laracasts.com/series/laravel-5-fundamentals/episodes/22)
    - [Laracasts: Syncing Tags](https://laracasts.com/series/laravel-5-fundamentals/episodes/23)
    - [Laracasts: Enhancing Select Elements](https://laracasts.com/series/laravel-5-fundamentals/episodes/24) \#Front End \#Elixir
    - [Laracasts: When You Want a View Partial to Always Receive Data](https://laracasts.com/series/laravel-5-fundamentals/episodes/25)
    - [Laracasts: Loose Ends and Wrapping Up](https://laracasts.com/series/laravel-5-fundamentals/episodes/27)

## Tutorial

- [Laracasts](https://laracasts.com/)
- [Tuts+](http://code.tutsplus.com/categories/php/courses)
- [Sitepoint](http://www.sitepoint.com/php/)
- [Laravel Tricks](http://laravel-tricks.com/)
- [Laravel Recipes](http://laravel-recipes.com/)
- [Laravel Coding](http://laravelcoding.com/blog)

## Blogs

- [Taylor Otwell](http://taylorotwell.com/)
- [Matt Stauffer](https://mattstauffer.co/tags/laravel)
- [Mohammad Gufran](http://www.gufran.me/tag/Laravel/)
- [Adam Engebretson](http://blog.enge.me/4)
- [Sheikh Heera](http://heera.it/tag/laravel-2)
- [Kirk Bushell](http://kirkbushell.me/)
- [Andrews Ang](http://blog.kongnir.com/category/laravel-2/)
- [Jens Segers](https://jenssegers.com/)
- [Neon Tsunami](http://www.neontsunami.com/tags/laravel)
- [Scott Wilcox](http://dor.ky/tag/laravel/)
- [Stillat](http://www.stillat.com/blog/category/programming/laravel/)
- [Bosnadev](https://bosnadev.com/tag/laravel-2/)

## Newsletters

- [Laravel News](https://laravel-news.com)
- [Laravel Weekly](http://laravelweekly.com)
- [PHP Weekly](http://www.phpweekly.com/archive.html)
- [Securing PHP](http://securingphp.com/)

## Open Source Laravel

- [Laravel Framework](https://github.com/laravel/framework)
- [Laravel Application](https://github.com/laravel/laravel)
- [Laravel Documentation](https://github.com/laravel/docs)
- [Laravel Cashier](https://github.com/laravel/cashier)
- [Laravel Envoy](https://github.com/laravel/envoy)
- [Laravel Homestead](https://github.com/laravel/homestead)
- [Laravel Homestead Build Scripts](https://github.com/laravel/settler)
- [Laravel Website](https://github.com/laravel/laravel.com)
- [Laravel Art](https://github.com/laravel/art)

## Coding Standard

- [PHP The Right Way](http://www.phptherightway.com/)
- [PHP FIG](http://www.php-fig.org/)
- [PHP Framework Interoperability Group](https://github.com/php-fig/fig-standards)
- [Code Style Fixer](https://github.com/FriendsOfPHP/PHP-CS-Fixer)

## Dependency Management

- [Composer](http://getcomposer.org/)/[Packagist](http://packagist.org/) - A package and dependency manager

## Develop Tools

- [Sublime Text](http://www.sublimetext.com/)
  - [Alignment](https://github.com/wbond/sublime_alignment) - Easy alignment of multiple selections and multi-line selections
  - [Blade Snippets](https://github.com/dev4dev/blade-snippets) - Provide snippets for blade template engine
  - [BracketHighlighter](https://github.com/facelessuser/BracketHighlighter) - Bracket and tag highlighter
  - [DocBlockr](https://github.com/spadgos/sublime-jsdocs) - Simplifies writing DocBlock comments
  - [Emmet](https://github.com/sergeche/emmet-sublime) - Improves HTML & CSS workflow
  - [Laravel Blade Highlighter](https://github.com/Medalink/laravel-blade) - Adds syntax definitions for the Laravel 5 Blade engine
  - [phpfmt](https://github.com/phpfmt/sublime-phpfmt) - Plugin to format PHP code - supports also PSR1/2
  - [Sidebar Enhancements](https://github.com/titoBouzout/SideBarEnhancements) - Enhancements to Sublime Text sidebar
  - [SublimeCodeIntel](https://github.com/SublimeCodeIntel/SublimeCodeIntel) - Full-featured code intelligence and smart autocomplete engine
  - [SublimeLinter](https://github.com/SublimeLinter/SublimeLinter3) - Interactive code linting framework, you have to install SublimeLinter-php too for coding in PHP
  - [SublimeLinter-php](https://github.com/SublimeLinter/SublimeLinter-php) - SublimeLinter plugin for PHP
  - [Syntax Highlighting for Sass](https://github.com/P233/Syntax-highlighting-for-Sass) - Syntax highlighting for both SCSS and Sass
  - [Trailing Spaces](https://github.com/SublimeText/TrailingSpaces) - Highlight trailing spaces and delete them
- [PhpStorm IDE ](https://www.jetbrains.com/phpstorm/)
  - [Laravel Plugin for PhpStorm](https://github.com/Haehnchen/idea-php-laravel-plugin)

## PHP Book List for Developer

- Getting Started
  - Learning PHP, MySQL & JavaScript With jQuery, CSS & HTML5, 4th edition ISBN:9781491918661
  - Programming PHP, Third Edition ISBN:9781449361068
  - Learning PHP, MySQL, JavaScript, and CSS, 2nd Edition ISBN:9781449319267
  - Head First PHP & MYSQL ISBN:9781449363581
  - Head First HTML and CSS, 2nd Edition ISBN:9780596159900
- Advanced
  - Laravel: From Apprentice To Artisan
  - Laravel Testing Decoded
  - Laravel 5.1 Beauty
  - Modern PHP: New Features and Good Practices ISBN:9781491905012
  - Learning PHP Design Patterns ISBN:9781449344917
  - Beautiful Testing: Leading Professionals Reveal How They Improve Software ISBN:9780596159818
  - PHP Master: Write Cutting Edge Code ISBN:9780987090874
  - Laravel 5 Essentials: Explore the Fundamentals of Laravel, One of the Most Expressive and Robust Php Frameworks ISBN:9781785283017
  - Laravel Design Patterns and Best Practices ISBN:9781783287987
  - Learning Laravel's Eloquent ISBN:9781784391584
- Concept
  - Head First Object-Oriented Analysis and Design ISBN:9780596008673
  - Head First Design Patterns ISBN:0000596007124
  - Refactoring: Improving the Design of Existing Code ISBN:9780201485677
  - Design Patterns: Elements of Reusable Object-Oriented Software ISBN:9780201633610
  - Scrum: The Art of Doing Twice the Work in Half the Time ISBN:9781847941107
  - Clean Code: A Handbook of Agile Software Craftsmanship ISBN:9780132350884
  - The Clean Coder: A Code of Conduct for Professional Programmers ISBN:0076092046981
  - Continuous Delivery: Reliable Software Releases through Build, Test, and Deployment Automation ISBN:9780321601919
  - Beautiful Architecture: Leading Thinkers Reveal the Hidden Beauty in Software Design ISBN:9780596517984
  - The Art of Readable Code ISBN:9780596802295
  - Design Patterns Explained: A New Perspective on Object-Oriented Design ISBN:9780321247148
  - Apprenticeship Patterns: Guidance for the Aspiring Software Craftsman ISBN: 9780596518387
  - Quality Code: Software Testing Principles, Practices, and Patterns ISBN:9780321832986
  - Implementation Patterns ISBN:0785342413090

## Interview

- [Awesome PHP Interview Questions](https://github.com/MaximAbramchuck/awesome-interviews#php)

# Chinese Version / 中文版

## 索引

- [Laravel 新手村](#user-content-laravel-新手村)
- [快速參考](#user-content-快速參考)
- [影片及文章](#user-content-影片及文章)
  - [Composer / Homestead](#user-content-composer--homestead-1)
  - [路由 / 控制器 / 請求 / 回應 / 視圖](#user-content-路由--控制器--請求--回應--視圖)
  - [Blade](#user-content-blade-1)
  - [系統架構](#user-content-系統架構)
  - [資料庫](#user-content-資料庫)
  - [Eloquent](#user-content-eloquent-1)
  - [表單 / 驗證](#user-content-表單--驗證)
  - [認證](#user-content-認證)
  - [中介層](#user-content-中介層)
  - [前端整合](#user-content-前端整合)
  - [Session](#user-content-session-1)
  - [檔案系統與雲端儲存](#user-content-檔案系統與雲端儲存)
  - [快取](#user-content-快取)
  - [郵件](#user-content-郵件)
  - [測試與程式碼風格標準](#user-content-測試與程式碼風格標準)
- [教學網站](#user-content-教學網站)
- [部落格](#user-content-部落格)
- [電子報](#user-content-電子報)
- [Laravel 開源碼](#user-content-laravel-開源碼)
- [程式碼風格標準](#user-content-程式碼風格標準)
- [相依管理](#user-content-相依管理)
- [開發工具](#user-content-開發工具)
- [給 PHP 開發者的書單](#user-content-給-php-開發者的書單)
- [面試](#user-content-面試)
- [社群](#user-content-社群)

## Laravel 新手村

- [Laravel 5 基礎](https://laracasts.com/series/laravel-5-fundamentals)
- Laravel 5.1 Homestead 安裝指南
  - [Homestead 2.0 on windows 7/8](http://yish.im/2015/07/28/Homestead-2-0-on-windows7-8/)
  - [Homestead 2.0 on Ubuntu](http://yish.im/2015/03/22/Homestead-2-0-on-Ubuntu/)
  - [Laravel Homestead on Linux or Mac](https://laravel.tw/docs/5.1/homestead)
  - [向 Laravel Homestead 2.0 說 Hello](https://laracasts.com/lessons/say-hello-to-laravel-homestead-two)
- [在 AWS EC2 上快速架好符合 Laravel 運行的環境](https://github.com/fukuball/ec2-laravel-evn-installer)
- 新手做中學
  - [基本任務清單](https://laravel.tw/docs/5.1/quickstart)
  - [中級任務清單](https://laravel.tw/docs/5.1/quickstart-intermediate)
- [Laravel 文件](https://laravel.tw/docs/5.1)
- 跟著 Laravel 5.1 一起成為更好的 PHP 開發者 [影片](https://www.youtube.com/watch?v=al2eCFvvM-s&feature=youtu.be) [投影片](http://www.slideshare.net/shengyou/phpconf-taiwan-2015-laravel-51-php)

## 快速參考

- [偉哉 Laravel](https://github.com/chiraggude/awesome-laravel)
- [偉哉 PHP](https://github.com/ziadoz/awesome-php)
- [Laravel API](http://laravel.com/api/5.1/)

## 影片及文章

### Composer / Homestead

- 第一級
  - [Meet Composer](https://laracasts.com/series/laravel-5-fundamentals/episodes/1)
  - [Virtual Machines and Homestead](https://laracasts.com/series/laravel-5-fundamentals/episodes/2)
  - [Composer](https://getcomposer.org/doc/00-intro.md)
  - [設定 Homestead](https://laravel.tw/docs/5.1/homestead)

### 路由 / 控制器 / 請求 / 回應 / 視圖

- 第一級
  - [A Gentle Introduction to Routing, Controllers, and Views](https://laracasts.com/series/laravel-5-fundamentals/episodes/3)
  - [Passing Data to Views](https://laracasts.com/series/laravel-5-fundamentals/episodes/4)
  - [基本功能 路由](https://laravel.tw/docs/5.1/routing)
  - [基本功能 控制器](https://laravel.tw/docs/5.1/controllers)
  - [基本功能 請求](https://laravel.tw/docs/5.1/requests)
  - [基本功能 回應](https://laravel.tw/docs/5.1/responses)
  - [基本功能 視圖](https://laravel.tw/docs/5.1/views)
  - [Basic Model/Controller/View Workflow](https://laracasts.com/series/laravel-5-fundamentals/episodes/9)
- 第二級
  - [View Partials and Form Reuse](https://laracasts.com/series/laravel-5-fundamentals/episodes/13)
  - [Route Model Binding](https://laracasts.com/series/laravel-5-fundamentals/episodes/18)

### Blade

- 第一級
  - [Blade 101](https://laracasts.com/series/laravel-5-fundamentals/episodes/5)
  - [基本功能 Blade 模板](https://laravel.tw/docs/5.1/blade)

### 系統架構

- 第一級
  - [Environments and Configuration](https://laracasts.com/series/laravel-5-fundamentals/episodes/6)
  - [系統架構 應用程式結構](https://laravel.tw/docs/5.1/structure)
- 第二級
  - [系統架構 請求的生命週期](https://laravel.tw/docs/5.1/lifecycle)
  - [系統架構 服務提供者](https://laravel.tw/docs/5.1/providers)
  - [系統架構 服務容器](https://laravel.tw/docs/5.1/container)
  - [系統架構 Contracts](https://laravel.tw/docs/5.1/contracts)
  - [系統架構 Facades](https://laravel.tw/docs/5.1/facades)

### 資料庫

- 第一級
  - [Migrations](https://laracasts.com/series/laravel-5-fundamentals/episodes/7)
  - [資料庫 入門](https://laravel.tw/docs/5.1/database)
  - [資料庫 遷移](https://laravel.tw/docs/5.1/migrations)
- 第二級
  - [資料庫 查詢建構器](https://laravel.tw/docs/5.1/queries)
  - [資料庫 資料填充](https://laravel.tw/docs/5.1/seeding)

### Eloquent

- 第一級
  - [Eloquent 101](https://laracasts.com/series/laravel-5-fundamentals/episodes/8)
  - [Eloquent ORM 入門](https://laravel.tw/docs/5.1/eloquent)
- 第二級
  - [Eloquent ORM 關聯](https://laravel.tw/docs/5.1/eloquent-relationships)
  - [Eloquent ORM 集合](https://laravel.tw/docs/5.1/eloquent-collections)
  - [Eloquent ORM 存取器](https://laravel.tw/docs/5.1/eloquent-mutators)
  - [Eloquent ORM 序列化](https://laravel.tw/docs/5.1/eloquent-serialization)
  - [Eloquent Relationships](https://laracasts.com/series/laravel-5-fundamentals/episodes/14)
  - [Many to Many Relations (With Tags)](https://laracasts.com/series/laravel-5-fundamentals/episodes/21)

### 表單 / 驗證

- 第一級
  - [Forms](https://laracasts.com/series/laravel-5-fundamentals/episodes/10)
  - [Dates, Mutators, and Scopes](https://laracasts.com/series/laravel-5-fundamentals/episodes/11)
  - [Form Requests and Controller Validation](https://laracasts.com/series/laravel-5-fundamentals/episodes/12)
  - [系統服務 驗證](https://laravel.tw/docs/5.1/validation)

### 認證

- 第一級
  - [Easy Auth](https://laracasts.com/series/laravel-5-fundamentals/episodes/15)
  - [系統服務 認證](https://laravel.tw/docs/5.1/authentication)
  - [系統服務 授權](https://laravel.tw/docs/5.1/authorization)

### 中介層

- 第一級
  - [Ogres Are Like Middleware](https://laracasts.com/series/laravel-5-fundamentals/episodes/16)
  - [基本功能 中介層](https://laravel.tw/docs/5.1/middleware)

### 前端整合

- 第一級
  - [Manage Your Assets](https://laracasts.com/series/laravel-5-fundamentals/episodes/19)
  - [系統服務 Elixir](https://laravel.tw/docs/5.1/elixir)

### Session

- 第一級
  - [Flash Messaging](https://laracasts.com/series/laravel-5-fundamentals/episodes/20)
  - [系統服務 Session](https://laravel.tw/docs/5.1/session)

### 檔案系統與雲端儲存

- 第一級
  - [系統服務 檔案系統與雲端儲存](https://laravel.tw/docs/5.1/filesystem)

### 快取

- 第一級
  - [系統服務 快取](https://laravel.tw/docs/5.1/cache)

### 郵件

- 第一級
  - [系統服務 郵件](https://laravel.tw/docs/5.1/mail)

### 測試與程式碼風格標準

- 第一級
  - [系統服務 測試](https://laravel.tw/docs/5.1/testing)

## 教學網站

- [Laravel 道場](http://www.laravel-dojo.com/)
- [laravel.so](http://laravel.so/)
- [Laracasts](https://laracasts.com/)
- [Tuts+](http://code.tutsplus.com/categories/php/courses)
- [Sitepoint](http://www.sitepoint.com/php/)
- [Laravel Tricks](http://laravel-tricks.com/)
- [Laravel Recipes](http://laravel-recipes.com/)
- [Laravel Coding](http://laravelcoding.com/blog)

## 部落格

- [Yish.im](http://yish.im/)
- [點燈坊](http://oomusou.io/)
- [JIgsaw's Notes](http://notes.jigsawye.com/)
- [sharenjoy 享享](http://blog.sharenjoy.com/)
- [轉個彎日誌](http://blog.turn.tw/?variant=zh-tw)
- [網站製作學習誌](http://jaceju.net/)

## 電子報

- [碼天狗週刊](http://weekly.codetengu.com)
- [Laravel News](https://laravel-news.com)
- [Laravel Weekly](http://laravelweekly.com)
- [PHP Weekly](http://www.phpweekly.com/archive.html)
- [Securing PHP](http://securingphp.com/)

## Laravel 開源碼

- [Laravel Framework](https://github.com/laravel/framework)
- [Laravel Application](https://github.com/laravel/laravel)
- [Laravel 中文文件](https://github.com/laravel-taiwan/docs)
- [Laravel Cashier](https://github.com/laravel/cashier)
- [Laravel Envoy](https://github.com/laravel/envoy)
- [Laravel Homestead](https://github.com/laravel/homestead)
- [Laravel Homestead Build Scripts](https://github.com/laravel/settler)
- [Laravel Website](https://github.com/laravel/laravel.com)
- [Laravel Art](https://github.com/laravel/art)

## 程式碼風格標準

- [PHP The Right Way](http://laravel-taiwan.github.io/php-the-right-way/)
- [PHP FIG](http://www.php-fig.org/)
- [fig-standards](https://github.com/laravel-taiwan/fig-standards/tree/master/accepted/zh-TW)
- [Code Style Fixer 程式碼風格修復器](https://github.com/FriendsOfPHP/PHP-CS-Fixer)

## 相依管理

- [Composer](http://getcomposer.org/)/[Packagist](http://packagist.org/) - 使用 Compoer 套件管理工具，可以在 Packagist 搜尋想使用的套件

## 開發工具

- [Sublime Text](http://www.sublimetext.com/)
  - [Alignment](https://github.com/wbond/sublime_alignment) - 快速對齊多行程式碼
  - [Blade Snippets](https://github.com/dev4dev/blade-snippets) - 提供 Laravel 常用的 Code Snippets
  - [BracketHighlighter](https://github.com/facelessuser/BracketHighlighter) - 游標移到大括號或是一般的括號就會有明顯的高亮顯示
  - [DocBlockr](https://github.com/spadgos/sublime-jsdocs) - 簡化註解的撰寫
  - [Emmet](https://github.com/sergeche/emmet-sublime) - 輔助快速產生 HTML 與 CSS 語法的套件
  - [Laravel Blade Highlighter](https://github.com/Medalink/laravel-blade) - 讓 Laravel Blade 的關鍵字高亮
  - [phpfmt](https://github.com/phpfmt/sublime-phpfmt) - 存檔時，將 PHP Code 自動修成符合標準
  - [Sidebar Enhancements](https://github.com/titoBouzout/SideBarEnhancements) - Enhancements to Sublime Text sidebar - 替側邊欄新增許多實用的操作功能
  - [SublimeCodeIntel](https://github.com/SublimeCodeIntel/SublimeCodeIntel) - 程式碼追蹤套件，讓 Sublime 有自動完成功能
  - [SublimeLinter](https://github.com/SublimeLinter/SublimeLinter3) - 程式碼錯誤檢查工具，不過只裝這個是沒有作用的，要另外依照不同程式碼安裝相對應的套件，例如下面介紹的 SublimeLinter-php
  - [SublimeLinter-php](https://github.com/SublimeLinter/SublimeLinter-php) - PHP 錯誤檢查工具
  - [Syntax Highlighting for Sass](https://github.com/P233/Syntax-highlighting-for-Sass) - 讓 SCSS 及 Sass 關鍵字高亮
  - [Trailing Spaces](https://github.com/SublimeText/TrailingSpaces) - 自動刪除多餘的空白
- [PhpStorm IDE](https://www.jetbrains.com/phpstorm/)
  - [Laravel Plugin for PhpStorm](https://github.com/Haehnchen/idea-php-laravel-plugin)

## 給 PHP 開發者的書單

- 入門
  - PHP、MySQL 與 JavaScript 學習手冊 (第四版) ISBN：9789863476726
  - PHP 程式設計 (第三版) ISBN：9789862769881
  - PHP、MySQL、JavaScript 與 CSS 學習手冊 (第二版) ISBN：9789862766576
  - 深入淺出 PHP 與 MySQL ISBN：9789866840401
  - 深入淺出 HTML&CSS (第二版) ISBN：9789862768945
- 進階
  - Laravel: From Apprentice To Artisan
  - Laravel Testing Decoded
  - Laravel 5.1 Beauty
  - 現代 PHP：新的特點及良好習慣 ISBN：9789863477785
  - PHP 設計模式學習手冊 ISBN：9789862767702
  - 測試之美 ISBN：9789862763445
  - PHP 大師：寫出頂尖的程式碼 ISBN：9789862765142
  - Laravel 5 Essentials: Explore the Fundamentals of Laravel, One of the Most Expressive and Robust Php Frameworks ISBN：9781785283017
  - Laravel Design Patterns and Best Practices ISBN：9781783287987
  - Learning Laravel's Eloquent ISBN: 9781784391584
- 觀念
  - 深入淺出物件導向分析與設計 ISBN：9789867794994
  - 深入淺出－設計模式 ISBN：9867794524
  - 大話設計模式 ISBN：9789866761799
  - 大話重構 ISBN：9789864340460
  - 大話資料結構 ISBN：9789866072116
  - 重構－改善既有程式的設計 ISBN：9861547533
  - 重構－向範式前進 ISBN：9861814027
  - 物件導向設計模式－可再利用物件導向軟體之要素(精裝典藏版) ISBN：9572054112
  - SCRUM：用一半的時間 做兩倍的事 ISBN：9863207144
  - 無瑕的程式碼－敏捷軟體開發技巧守則 ISBN：9862017058
  - 無瑕的程式碼 番外篇－專業程式設計師的生存之道 ISBN：9862017880
  - Continuous Delivery 中文版：利用自動化的建置、測試與部署完美創造出可信賴的軟體發佈 ISBN：9789862019627
  - 架構之美：頂尖架構師於軟體設計中蘊含的智慧結晶 ISBN：9789862763988
  - 易讀程式之美學：提升程式碼可讀性的簡單法則 ISBN：9789862767191
  - 設計模式的解析與活用 ISBN：9789862018200
  - 代碼之髓：編程語言核心概念 ISBN：9787115361530
  - 松本行弘談程式世界的未來 ISBN：9789863473312
  - 松本行弘的程式世界：成為一流程式設計師的14種思考術  ISBN：9789862013571
  - 學徒模式－優秀軟體開發者的養成之路 ISBN: 9789862762561
  - 高品質程式：軟體測試原則、實作與模式 ISBN：9789863473060
  - Kent Beck 的實作模式 ISBN：9789862018088

## 面試

- [偉哉 PHP 面試問題](https://github.com/MaximAbramchuck/awesome-interviews#php)

## 社群

- [Laravel 台灣](https://www.facebook.com/groups/laravel.tw/)
- [PHP 也有 Day](https://www.facebook.com/groups/849639948396465/)
- [PHP 台灣 Slack](https://phptw.slack.com/messages/laravel/)

# Contributing Guidelines / 貢獻指南

- Contributing Guidelines
  - Please make an individual pull request for each suggestion
  - New categories or improvements to the existing categorization are welcome

- 貢獻指南
  - 請每項建議發出個別的 pull request
  - 新的類別跟既存類別的改善都歡迎

# Special Thanks / 特別感謝

Special Thanks to [Laravel 台灣](https://www.facebook.com/groups/laravel.tw/)!

特別感謝 [Laravel 台灣](https://www.facebook.com/groups/laravel.tw/)！

# License

The MIT License (MIT)

Copyright (c) 2015 fukuball

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
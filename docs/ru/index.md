# Документация
----------

## Добро пожаловать

Это руководство содержит справочную информацию и охватывает наиболее важные темы разработки бизнес-приложений с использованием платформы ORCHID.

Для использования платформы требуется знание следующих технологий:
- PHP/JavaScript/HTML/CSS
- Реляционных баз данных
- Apache/nginx
- Laravel Framework


> Для предложения улучшений этого руководства, создайте новый [issue](https://github.com/orchidsoftware/platform/issues). 
В случаи ошибоки в документации, пожалуйста, укажите главу и сопутсвующий текст, чтобы указать на ошибку.


Перед установкой и использованием, рекомендуем получить общие сведения, о том какие задачи решает платформа. Эта небольшая трата времени может помочь вам в долгосрочной перспективе.


## Введение

ORCHID - инструмент, для [RAD](https://ru.wikipedia.org/wiki/RAD_(%D0%BF%D1%80%D0%BE%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5)) разработки веб-сайтов и линейные бизнес-приложения. 
Поставляется в виде пакета для Laravel и легко интегрируется с помощью Composer, он 
 также хорошо сочетается с другими компонентами PHP. 
 Вы можете зарегистрировать дополнительные сторонние компоненты для Laravel или найденные в [Packagist](https://packagist.org/).

Большинство бизнес-приложений относится к типу "формы поверх данных" и предоставляет пользовательский интерфейс для просмотра, добавления и изменения данных.
Когда вы используете другие средства разработки для создания приложений типа "формы поверх данных", значительная часть времени уходит на выполнение повторяющихся задач. 
Вы пишите код для взаимодействия с базой данных, код для пользовательского интерфейса и код для бизнес-логики.
 
Использование ORCHID избавляет вас от многих повторяющихся задач, требуется написать только один вид кода — бизнес-логику.


## Как читать документацию

Если вы новичок, я рекомендую вам прочитать документацию «Laravel» от начала до конца, например, на [laravel.su](http://laravel.su/docs).
Документация ORCHID не поясняет возможности фреймворка. Если вы уже знакомы с ним, вы можете перейти к прочтению следующих глав.

Эта документация начинается с объяснения концепции и архитектуры ORCHID, прежде чем углубиться в конкретные темы.


## Возможности для бизнес-приложений

Современным бизнес-приложениям требуется множество возможностей, например: поиска, сортировки и переупорядочения сеток, а также экспорта данных.
Все эти и многие другие возможности уже встроены в приложения ORCHID. Кроме того, типичные операции с данными, такие как добавление, обновление, сохранение и удаление, тоже уже встроены в виде базовой логической схемы проверки данных.

Используя пользовательские элементы управления и расширения вы можете использовать настраиваемые типы полей для сокращения создаваемого объема кода и упрощения форматирования в пользовательском интерфейсе.


## Итоги 

ORCHID берет на себя все рутинные операции по разработке бизнес-приложений, предоставляя пользователям возможность сосредоточиться на уникальной бизнес-логике, соответствующей необходимым требованиям. 

Несмотря на кажущуюся простоту, позволяет решить множество задач с помощью стандартных средств, а при необходимости расширять собственными функциями.


Следуя [инструкции](/docs/installation/) Вы быстро установите и будете готовы к ее использованию.

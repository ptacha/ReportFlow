<div align="justify">

<p><strong>ReportFlow</strong> ist eine kostenlose Open-Source-Anwendung für Windows 10 und 11 zur automatisierten Datenverarbeitung und Berichterstellung.</p>

<div class="reportflow-intro">
<img class="reportflow-logo" src="assets/images/ptacha.png" alt="ReportFlow-Logo: blauer Faltvogel mit dem Schriftzug ptacha" width="180" height="180" align="left">
<p>Die zentrale Einheit der Anwendung ist ein <strong>Szenario</strong>, das aus mehreren <strong>Aufgaben</strong> besteht und sich speichern und erneut ausführen lässt. Dadurch werden aufeinanderfolgende Berichte nach denselben Regeln erstellt, ohne jedes Mal sich Mühe zu geben, den Aufwand selbst zu tragen.</p>
<p>Zur besseren Übersicht sind die Aufgaben durch Linien miteinander verbunden und bilden ein grafisches Ablaufdiagramm. Die Filter zeigen eingehende und ausgehende Verbindungen (Eingehend, Ausgehend). Außerdem lassen sich Nebenlinien in den Hintergrund rücken (Nebenlinien) und ungenutzte Aufgaben hervorheben (Ungenutzt).</p>
<p>Alle Prozesse laufen auf dem eigenen Rechner ab und benötigen keine Internetverbindung.</p>
<p>Die Anwendung wird mit <strong>Python 3.13.14</strong> erstellt. Die fertige Windows-Version enthält bereits die benötigte Python-Umgebung.</p>
<br class="reportflow-intro-clear" clear="all">
</div>
<h2>Aufgaben</h2>
<table id="tasks-overview">
<tbody>
<tr>
<th scope="col" align="center">Datenquellen</th>
<th scope="col" align="center">Transformationen</th>
</tr>
<tr>
<td>
<ul>
<li>Erstellung einer Dateiliste aus Ordnern</li>
<li>Erstellung einer Dateiliste aus ZIP-Archiven</li>
<li>Import einer CSV-Datei</li>
<li>Import einer Excel-Datei</li>
<li>Import einer MDB-Datei</li>
<li>Zusammenführung mehrerer CSV-Dateien</li>
<li>Extraktion von Daten aus XML-Dateien</li>
<li>Analyse von PDF-Dateien</li>
<li>Erkennung von Barcodes in PDF-Dateien</li>
</ul>
</td>
<td>
<ul>
<li>Berechnung von Spaltenwerten</li>
<li>Zusammenführung von Spaltenwerten</li>
<li>Konvertierung von Spaltentypen</li>
<li>Ersetzung von Werten in Spalten</li>
<li>Filterung von Zeilen nach Bedingungen</li>
<li>Sortierung von Zeilen nach Spalten</li>
<li>Entfernung von Duplikaten</li>
<li>Datenaudit</li>
</ul>
</td>
</tr>
<tr>
<th scope="col" align="center">Verknüpfungen</th>
<th scope="col" align="center">Ausgabe</th>
</tr>
<tr>
<td>
<ul>
<li>Verknüpfung von Haupt- und Hilfstabelle</li>
<li>Konsolidierung mehrerer Tabellen über Schlüssel</li>
<li>Zusammenführung von Tabellen untereinander</li>
</ul>
</td>
<td>
<ul>
<li>Export von Tabellen nach Excel</li>
<li>Export von Zeilen nach CSV (zeilenweise)</li>
</ul>
</td>
</tr>
</tbody>
</table>
<h2>Releases und Kontakt</h2>
<div class="reportflow-link-cards">
<p><a class="reportflow-link-card reportflow-downloads" href="https://github.com/ptacha/ReportFlow/releases" target="_blank" rel="noopener noreferrer"><img src="assets/icons/downloads.svg" alt="" width="40" height="40"><br><span>Downloads</span></a></p>
<p><a class="reportflow-link-card reportflow-feedback" href="https://github.com/ptacha/ReportFlow/issues" target="_blank" rel="noopener noreferrer"><img src="assets/icons/feedback.svg" alt="" width="40" height="40"><br><span>Fragen und Feedback</span></a></p>
</div>
<h2>Lizenz und Copyright</h2>
<p><strong>Copyright © 2025–2026 Andrey Shpak</strong><br>Ursprüngliche Idee, Konzeption und Umsetzung: Andrey Shpak</p>
<p>ReportFlow steht unter der <a href="LICENSE">GNU Affero General Public License, Version 3 (AGPLv3)</a>.</p>
<p>ReportFlow darf unter den Bedingungen dieser Lizenz genutzt, geändert und weitergegeben werden. Die ursprünglichen Copyright- und Lizenzhinweise müssen bei einer Weitergabe erhalten bleiben. Die vollständigen Bedingungen stehen in der Lizenzdatei.</p>
<p><strong>Bei der Entwicklung werden KI-gestützte Werkzeuge unterstützend eingesetzt. Das Programmsymbol wurde mit Hilfe von KI erstellt.</strong></p>
<p>Verwendete Komponenten anderer Anbieter haben eigene Urheberrechte und Lizenzen. Die Hinweise dazu stehen im Programm unter <strong>Copyright und Lizenzen</strong>.</p>
<h2>Hinweise zu Versionen</h2>
<table id="version-history">
<thead>
<tr>
<th><div align="justify">Version</div></th>
<th><div align="justify">Beschreibung</div></th>
</tr>
</thead>
<tbody><tr>
<td><div align="justify"><strong>0.1</strong></div></td>
<td><div align="justify"><strong>Середина 2025 года. Внутренняя разработка.</strong> Отдельные независимые скрипты обработки данных без графического интерфейса. Управление осуществлялось через диалоги командной строки</div></td>
</tr>
<tr>
<td><div align="justify">0.2-0.2.2</div></td>
<td><div align="justify">Формирование сценарной архитектуры, объединение 17 задач обработки данных, создание первых элементов графического интерфейса</div></td>
</tr>
<tr>
<td><div align="justify">0.3.0-0.5.0</div></td>
<td><div align="justify">Разработка визуальной настройки задач, мастера создания сценариев, контроля структуры колонок и системы предупреждений</div></td>
</tr>
<tr>
<td><div align="justify">0.6.0-0.6.9</div></td>
<td><div align="justify">Введение взаимосвязанных задач, предварительного просмотра результатов, расширенной поддержки CSV, XML и различных кодировок</div></td>
</tr>
<tr>
<td><div align="justify">0.7.0-0.7.6</div></td>
<td><div align="justify">Поддержка параллельного выполнения сценариев, улучшение управления обработкой, цветовых категорий и графического интерфейса</div></td>
</tr>
<tr>
<td><div align="justify"><strong>0.7.7 Alpha</strong></div></td>
<td><div align="justify"><strong>Переименование FileFlow в IM ReportFlow.</strong> Начало альфа-этапа разработки специализированной системы обработки данных с дальнейшим расширением функциональности и тестированием</div></td>
</tr>
<tr>
<td><div align="justify">0.7.8-0.7.28</div></td>
<td><div align="justify">Переработка редактора задач, адаптивное расположение элементов, немецкий интерфейс и расширение автоматических проверок</div></td>
</tr>
<tr>
<td><div align="justify">0.7.63-0.7.84</div></td>
<td><div align="justify">Оптимизация обработки CSV, Excel и MDB, внедрение консолидации таблиц по ключам, повышение совместимости компонентов</div></td>
</tr>
<tr>
<td><div align="justify">1.0.0-1.0.10</div></td>
<td><div align="justify">Введение компактных карточек, контроля зависимостей, статусов выполнения, блокировки сценариев и двухэтапной настройки задач</div></td>
</tr>
<tr>
<td><div align="justify">2.0.0.8-2.0.0.16</div></td>
<td><div align="justify">Упрощение интерфейса, совершенствование объединения таблиц и удаление устаревших программных компонентов</div></td>
</tr>
<tr>
<td><div align="justify"><strong>3.x Beta</strong></div></td>
<td><div align="justify"><strong>Переименование IM ReportFlow в ReportFlow.</strong> Отказ от специализированной направленности и переход к универсальной программе обработки структурированных данных. Начало бета-этапа развития</div></td>
</tr>
<tr>
<td><div align="justify">3.0.0.1-3.0.0.12</div></td>
<td><div align="justify">Переработка внутренней архитектуры, улучшение истории выполнения, документации и обработки XML</div></td>
</tr>
<tr>
<td><div align="justify">3.0.0.13-3.0.0.29</div></td>
<td><div align="justify">Обновление карточек задач, индикаторов прогресса, навигации и организации графического интерфейса</div></td>
</tr>
<tr>
<td><div align="justify">3.0.0.30-3.0.0.32</div></td>
<td><div align="justify">Унификация внутренних компонентов, обновление идентификаторов, путей и автоматических проверок</div></td>
</tr>
<tr>
<td><div align="justify">4.1.0.0-4.1.0.11</div></td>
<td><div align="justify">Стандартизация настройки задач, автоматическая проверка структуры входных данных и графическое представление зависимостей</div></td>
</tr>
<tr>
<td><div align="justify">4.2.0.0-4.2.0.45</div></td>
<td><div align="justify">Расширение функций преобразования, вычисления и обработки Excel, внедрение управляемого параллельного выполнения</div></td>
</tr>
<tr>
<td><div align="justify">4.3.0.3-4.3.1.1</div></td>
<td><div align="justify">Унификация типов данных, модульная организация архитектуры и оптимизация использования вычислительных ресурсов</div></td>
</tr>
<tr>
<td><div align="justify">4.3.2.0-4.3.2.17</div></td>
<td><div align="justify">Введение обязательной проверки сценариев, расширенного контроля колонок, форматов дат и доступности сетевых источников</div></td>
</tr>
<tr>
<td><div align="justify">4.3.2.22-4.3.2.68</div></td>
<td><div align="justify">Стабилизация Windows-сборки, совершенствование обработки данных, расширение автоматического тестирования и подготовка официального выпуска</div></td>
</tr>
<tr>
<td><div align="justify"><strong>5.0.0.1 Release</strong></div></td>
<td><div align="justify"><strong>Начало августа 2026 года. Первый официальный выпуск ReportFlow.</strong> Представление универсальной программы сценарной обработки структурированных данных для Windows, включающей полный набор из 19 задач, в том числе экспорт результатов в Excel</div></td>
</tr>
<tr>
<td><div align="justify">5.0.0.2-5.0.2.3</div></td>
<td><div align="justify">Улучшение документации, оптимизация обработки CSV, Excel и объединения таблиц, стабилизация сборки на Python 3.13 и упрощение интерфейса</div></td>
</tr>
<tr>
<td><div align="justify">6.0.0.1</div></td>
<td><div align="justify">Переход на модель распространения Freeware, обновление авторских прав, лицензий сторонних библиотек и состава дистрибутива</div></td>
</tr>
<tr>
<td><div align="justify">6.0.0.2</div></td>
<td><div align="justify">Подтверждение автономной обработки данных без подключения к интернету и удаление ненужных механизмов автоматической установки компонентов</div></td>
</tr>
<tr>
<td><div align="justify">6.1.0.1-6.1.0.13</div></td>
<td><div align="justify">Введение истории изменений сценариев, автоматического резервного копирования, гибкого размещения данных, описаний задач и улучшенного Excel-экспорта</div></td>
</tr>
<tr>
<td><div align="justify">6.2.0.1-6.2.0.15</div></td>
<td><div align="justify">Оптимизация объединения таблиц, форматирования Excel, отображения комментариев и стабильности графического интерфейса</div></td>
</tr>
<tr>
<td><div align="justify">6.2.1.0-6.3.0.17</div></td>
<td><div align="justify">Улучшение графического представления сценариев, управления соединительными линиями и автоматического расчёта расположения карточек, расширение GUI-тестирования</div></td>
</tr>
<tr>
<td><div align="justify"><strong>7.0 Final</strong></div></td>
<td><div align="justify"><strong>Начало октября 2026 года. Завершение основного этапа разработки ReportFlow.</strong> Переход к окончательной производственной версии универсальной программы, предназначенной для полноценной эксплуатации</div></td>
</tr>
<tr>
<td><div align="justify">7.0.0.1-7.0.0.7</div></td>
<td><div align="justify">Расширение анализа PDF, оптимизация массовой обработки файлов, повышение устойчивости выполнения и совершенствование автоматических проверок</div></td>
</tr>
<tr>
<td><div align="justify">7.0.0.8-7.0.0.15</div></td>
<td><div align="justify">Улучшение управления сценариями и задачами, предварительного просмотра результатов и системы исключений файлов и папок, исправления интерфейса</div></td>
</tr>
<tr>
<td><div align="justify">7.0.0.16-7.0.0.20</div></td>
<td><div align="justify">Стабилизация повторного использования результатов Excel внутри сценариев, расширение возможностей управления графическими соединениями и оптимизация отображения задач</div></td>
</tr>
<tr>
<td><div align="justify">7.0.0.21-7.1.0.1</div></td>
<td><div align="justify">Оптимизация экспорта Excel и предотвращение конфликтов имён файлов, улучшение проверки сетевых источников, совершенствование загрузки Excel-данных в SQLite и повышение стабильности обработки</div></td>
</tr>
<tr>
<td><div align="justify">7.1.0.2-7.1.0.6</div></td>
<td><div align="justify">Введение баланса записей с контролем источников и исключений, упрощение и структурирование настроек консолидации таблиц по ключам</div></td>
</tr>
<tr>
<td><div align="justify">7.1.0.7-7.1.0.9</div></td>
<td><div align="justify">Введение задачи аудита данных с проверкой значений колонок по настраиваемым условиям</div></td>
</tr>
<tr>
<td><div align="justify">7.2.0.1</div></td>
<td><div align="justify">Расширение обработки PDF внутри ZIP-архивов, введение задачи объединения значений колонок</div></td>
</tr>
<tr>
<td><div align="justify">7.2.0.2 Core</div></td>
<td><div align="justify">Увеличение скорости обработки по правилу 3-6-9 с динамическим контролем RAM (оперативной памяти) и CPU (процессора)</div></td>
</tr>
<tr>
<td><div align="justify">7.3.0.1</div></td>
<td><div align="justify">Добавление новой задачи по экспорту записей в CSV для создания мета-данных в формате CSV</div></td>
</tr>
<tr>
<td><div align="justify">7.3.0.2</div></td>
<td><div align="justify">Расширение анализа PDF с использованием qpdf и Poppler, выбором глубины проверки и определением заявленных стандартов вложенных файлов</div></td>
</tr>
<tr>
<td><div align="justify">7.3.1.1</div></td>
<td><div align="justify">Аварийный выход через диалоговое окно, дополнительная стабилизация CSV-настроек</div></td>
</tr>
<tr>
<td><div align="justify">7.3.1.2</div></td>
<td><div align="justify">Улучшение баланса записей и обработки файлов Excel (в связи со специфическими функциями некоторых файлов). Введение подсветки неиспользуемых таблиц в полном объеме</div></td>
</tr>
<tr>
<td><div align="justify"><strong>7.3.1.3 - по актуальную версию</strong></div></td>
<td><div align="justify">Введение избранных сценариев, цветовой индикации выполняющихся сценариев и защиты от удаления сценариев с открытыми файлами</div></td>
</tr>
</tbody></table>
</div>

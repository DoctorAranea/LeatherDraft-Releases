![LeatherDraft](images/splash.png)

# LeatherDraft

**Программа для выкроек изделий из кожи.** Чертите детали, ставьте швы с проколами под свой пробойник, печатайте выкройку
в натуральную величину или отдавайте на лазер и режущий плоттер.

[English below](#english)

## Скачать

**[Скачать установщик для Windows](https://github.com/DoctorAranea/LeatherDraft-Releases/releases/latest/download/LeatherDraft-win-Setup.exe)**

Все версии и что в них нового - на странице [выпусков](https://github.com/DoctorAranea/LeatherDraft-Releases/releases).

Программа бесплатная, в том числе для работы на продажу. Выкройки, сделанные в ней, принадлежат вам. Условия - в файле
[LICENSE.txt](LICENSE.txt).

## Что умеет

- Детали и вырезы, швы с проколами под ваш пробойник и шаг
- Связанные швы: на сшиваемых сторонах выходит одинаковое число проколов
- Совмещение строчек по месту: карман на стенке, ремешок на корпусе - проколы совпадают
- Метки совмещения, линии сгиба, шерфовка, стрелка направления тяги, размеры и осевые линии
- Фурнитура: кнопки, хольнитены, люверсы, прорези; половинки кнопки связываются в пару
- Зеркальные пары деталей: правка одной повторяется на другой
- Печать в натуральную величину на листах A4 и других, с нахлёстом и контрольным квадратом
- Экспорт в PDF, SVG и DXF для лазера и плоттера, открытие чертежей DXF, DWG и SVG

## Установка

1. Скачайте установщик и запустите его. Прав администратора не нужно: программа ставится для вашей учётной записи.
2. Windows может показать окно "Windows защитила ваш компьютер": у программы пока нет платной цифровой подписи. Нажмите
   "Подробнее", затем "Выполнить в любом случае".
3. Если на компьютере нет среды .NET 8, установщик скачает и поставит её сам.

Нужна Windows 10 или 11, 64 бита. Программа пока только на русском языке.

**Обновления** приходят сами: раз в день программа проверяет, не вышла ли новая версия, скачивает её и ставит, когда вы
закроете программу. Отключить это можно в настройках, раздел "Обновления".

**Удалить** программу можно как любую другую: "Параметры Windows" - "Приложения" - LeatherDraft. Ваши чертежи при этом
остаются на месте.

## Нашли ошибку или есть идея

Напишите в раздел [Issues](https://github.com/DoctorAranea/LeatherDraft-Releases/issues). Чтобы ошибку было проще найти,
укажите:

- версию программы - она в заголовке окна, например "LeatherDraft 0.9.0";
- что вы делали и что пошло не так;
- если программа сообщила об ошибке - приложите журнал `%LocalAppData%\LeatherDraft\logs\errors.log`;
- если ошибка связана с чертежом - приложите файл .ldraft.

---

<a id="english"></a>

## English

**LeatherDraft is a pattern maker for leather goods** for Windows 10 and 11 (64-bit). Draw pieces, add seams with holes
for your pricking iron, link seams so both sides get the same number of holes, place snaps and rivets, and print patterns
at 1:1 scale or export them to PDF, SVG and DXF for laser cutters and plotters.

**[Download the Windows installer](https://github.com/DoctorAranea/LeatherDraft-Releases/releases/latest/download/LeatherDraft-win-Setup.exe)**

The program is free, including for commercial work, and the patterns you make are yours (see [LICENSE.txt](LICENSE.txt)).
The interface is in Russian for now. If Windows SmartScreen warns about an unknown publisher, click "More info" and then
"Run anyway". The program updates itself. Bug reports and ideas are welcome in
[Issues](https://github.com/DoctorAranea/LeatherDraft-Releases/issues).

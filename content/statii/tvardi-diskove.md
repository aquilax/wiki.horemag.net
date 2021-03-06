---
title: "Твърди дискове 40GB"
date: 2005-07-03T06:03:57+01:00
---

## Кратка история на данните

Първите твърди дискове са били плод на експерименти. Изследователите, основно тези от IBM, са работили по няколко различни технолологии и концепции за да създадат диск, пригоден за пазара. Всъщност, първите устройства не са били дискове а цилиндрични барабани по повърхността на които се съхраняват данни върху магнитен слой. Тези барабани са били прекалено големи и трудни за употреба.

Първият истински твърд диск е имал глави които са били в контакт с повърхността на диска поради тяхната ниска чувствителност. За нещастие техологията за изготвянето на плочите е била далеч от днешното си равнище и след известен период на експлоатация, главите или плочите са се надрасквали.


Ключовият пробив, който дава възможност за създаването на модерните твърди дискове става през 1950 година. Инжинерите на IBM осъзнават че главите трябва да се поддържат над повърхността на диска и да четат битовете преминаващи под тях. </p>

Първият произведен диск е  IBM 305 RAMAC (Random Access Method of Accounting and Control), представен на 13 септември 1956 година. Той е можел да съхранява пет милиона символа (приблизително 5 Mb, символът по онова време е бил само 7 бита а не 8) върху повърхността на 50 плочи, всяка от които с диаметър 24 инча. Плътността му на запис е била около 2000 бита на квадратен инч.

През следващите години, технологията се усъвършенства; плътността на запис, капацитета и производителността се подобяват. През 1962 година IBM представя модела:1301 Advanced Disk File. Основното предимство на този диск е използването на нова технология при която глвавите “летят” над плочите носени от въздушен поток. По този начин разстоянието от главата до плочата се намалява на 800 до 250 микроича.

През 1973 година IBM представят модел 3340, който се смята за бащата на днешния твърд диск. Устройството има два отделни шпиндела, един фиксиран и един сменяем, всеки с капацитет 30 MB. По тази причина този диск е наричан и “30-30”. Поради това идва и другото му известно име “30-30” пушка Winchester. В този диск се намалява разстоянието от глвата до плочата на 17 микроинча. Съвременните твърди дискове използват много от технологиите залегнали в 3340, затова твърдите дискове все още се наричат Winchester дискове.

Първият 5.25” диск използван в персонални компютри е Seagate ST-506. Той има четири глави и капацитет 5 MB. IBM използва слеващият модел  ST-412, 10MB диск със същия размер в своите PC/XT и го праят първият широко използван диск.

40 GB дисковете са доста архаични в сравнение с техните 160+ GB техни наследници но те все още намират приложение на места където големината на диска е от второстепенно значение

## Тестове

За тестове получихме пет диска всеки от тях с капацитет 40 GB. Четри от дисковете са с 2 MB кеш и един с 8 MB. Тестовете бяха изпълнени на компютър със следната конфигурация:

<table>
<tr>
	<td>Операционна система</td>
	<td>Microsoft Windows 2000 Server Service Pack 4</td>
</tr>
<tr>
	<td>Процесор</td>
	<td>AMD Duron, 750 MHz</td>
</tr>
<tr>
	<td>Дънна платка</td>
	<td>Tomato Board PG133</td>
</tr>
<tr>
	<td>Чипсет на дънната платка</td>
	<td>VIA VT8365 ProSavage KM133</td>
</tr>
<tr>
	<td>Системна памет</td>
	<td>368 MB  (SDRAM</td>
</tr>
</table>

За тестове беше използван AIDA 32 Disk Benchmark на [AIDA32](http://www.aida32.hu/) v.3.88

<table width="100%" border="1" cellspacing="0" cellpadding="2">
<tr>
	<td colspan="6">Характеристики</td>
</tr>
<tr>
	<td>Модел</td>
	<td>ExcelStor Technology J340</td>
	<td>Maxtor 6E040L0</td>
	<td>ST340014A</td>
	<td>WDC WD400BB</td>
	<td>WDC WD400JB</td>
</tr>
<tr>
	<td>Версия</td>
	<td>V22OA63A</td>
	<td>NAR61590</td>
	<td>3.54</td>
	<td>09.01B09</td>
	<td>05.03E05</td>
</tr>
<tr>
	<td>Параметри</td>
	<td>цилиндри: 79780, глави: 16, сектори в писта: 63, байта в сектор: 512</td>
	<td>цилиндри: 79656, глави: 16, сектори в писта: 63, байта в сектор: 512</td>
	<td>цилиндри: 77545, глави: 16, сектори в писта: 63, байта в сектор: 512</td>
	<td>цилиндри: 77545, глави: 16, сектори в писта: 63, байта в сектор: 600</td>
	<td>цилиндри: 77545, глави: 16, сектори в писта: 63, байта в сектор: 600</td>
</tr>
<tr>
	<td>LBA сектори</td>
	<td>80418240</td>
	<td>80293248</td>
	<td>78165360</td>
	<td>78165360</td>
	<td>78165360</td>
</tr>
<tr>
	<td>Буфер</td>
	<td>1821 KB (Dual Ported, Read Ahead)</td>
	<td>2 MB (Dual Ported, Read Ahead)</td>
	<td>2 MB</td>
	<td>2 MB (Dual Ported, Read Ahead)</td>
	<td>8 MB (Dual Ported, Read Ahead)</td>
</tr>
<tr>
	<td>Максимален PIO режим</td>
	<td>PIO 4</td>
	<td>PIO 4</td>
	<td>PIO 4</td>
	<td>PIO 4</td>
	<td>PIO 4</td>
</tr>
<tr>
	<td>Максимален UDMA режим</td>
	<td>UDMA 5 (ATA-100)</td>
	<td>UDMA 6 (ATA-133)</td>
	<td>UDMA 5 (ATA-100)</td>
	<td>UDMA 5 (ATA-100)</td>
	<td>UDMA 5 (ATA-100)</td>
</tr>
<tr>
	<td>Неформатиран обем</td>
	<td>39267 MB</td>
	<td>39206 MB</td>
	<td>38167 MB</td>
	<td>44727 MB</td>
	<td>44727 MB</td>
</tr>
<tr>
	<td>SMART</td>
	<td>Поддържа се</td>
	<td>Поддържа се</td>
	<td>Поддържа се</td>
	<td>Поддържа се</td>
	<td>Поддържа се</td>
</tr>
<tr>
	<td>Режим на безопасност</td>
	<td>Поддържа се</td>
	<td>Поддържа се</td>
	<td>Поддържа се</td>
	<td>Поддържа се</td>
	<td>Поддържа се</td>
</tr>
<tr>
	<td>Управление на захранването</td>
	<td>Поддържа се</td>
	<td>Поддържа се</td>
	<td>Поддържа се</td>
	<td>Поддържа се</td>
	<td>Поддържа се</td>
</tr>
<tr>
	<td>Електро- захранване (APM)</td>
	<td>Поддържа се</td>
	<td>Поддържа се</td>
	<td>Не се поддържа</td>
	<td>Не се поддържа</td>
	<td>Не се поддържа</td>
</tr>
<tr>
	<td>Кеш запис</td>
	<td>Поддържа се</td>
	<td>Поддържа се</td>
	<td>Поддържа се</td>
	<td>Поддържа се</td>
	<td>Поддържа се</td>
</tr>
<tr>
	<td>Host Protected Area</td>
	<td>Поддържа се</td>
	<td>Поддържа се</td>
	<td>Поддържа се</td>
	<td>Поддържа се</td>
	<td>Поддържа се</td>
</tr>
<tr>
	<td>Power-Up In Standby</td>
	<td>Поддържа се</td>
	<td>Не се поддържа</td>
	<td>Не се поддържа</td>
	<td>Не се поддържа</td>
	<td>Не се поддържа</td>
</tr>
<tr>
	<td>Automatic Acoustic Management</td>
	<td>Поддържа се</td>
	<td>Поддържа се</td>
	<td>Не се поддържа</td>
	<td>Поддържа се</td>
	<td>Поддържа се</td>
</tr>
<tr>
	<td>48-bit LBA</td>
	<td>Поддържа се</td>
	<td>Не се поддържа</td>
	<td>Поддържа се</td>
	<td>Не се поддържа</td>
	<td>Не се поддържа</td>
</tr>
<tr>
	<td>Device Configuration Overlay</td>
	<td>Поддържа се</td>
	<td>Поддържа се</td>
	<td>Поддържа се</td>
	<td>Поддържа се</td>
	<td>Поддържа се</td>
</tr>
<tr>
	<td colspan="6">Физически данни</td>
</tr>
<tr>
	<td>Производител</td>
	<td>ExcelStor</td>
	<td>Maxtor</td>
	<td>Seagate</td>
	<td>Western Digital Corporation</td>
	<td>Western Digital Corporation</td>
</tr>
<tr>
	<td>Семейство</td>
	<td>Europa</td>
	<td>DiamondMax Plus 8</td>
	<td>Barracuda</td>
	<td>Caviar</td>
	<td>Caviar</td>
</tr>
<tr>
	<td>Форматиран обем</td>
	<td>40 GB</td>
	<td>40 GB</td>
	<td>40 GB</td>
	<td>40 GB</td>
	<td>40 GB</td>
</tr>
<tr>
	<td>Физически габарити</td>
	<td>146.6 x 101.6 x 25.4 mm</td>
	<td>146.1 x 101.6 x 17.5 mm</td>
	<td>146.99 x 101.6 x 26.035 mm</td>
	<td>147 x 101.6 x 25.4 mm</td>
	<td>147 x 101.6 x 25.4 mm</td>
</tr>
<tr>
	<td>Максимално тегло</td>
	<td>640 g</td>
	<td>510 g</td>
	<td>635 g</td>
	<td>600 g</td>
	<td>600 g</td>
</tr>
<tr>
	<td>Средна латентност</td>
	<td>4.17 ms</td>
	<td>4.17 ms</td>
	<td>4.16 ms</td>
	<td>4.20</td>
	<td>4.20</td>
</tr>
<tr>
	<td>Скорост на въртене</td>
	<td>7200 RPM</td>
	<td>7200 RPM</td>
	<td>7200 RPM</td>
	<td>7200 RPM</td>
	<td>7200 RPM</td>
</tr>
<tr>
	<td>Максимална скорост на вътрешни данни</td>
	<td>654 Мбита/с</td>
	<td>-</td>
	<td>683.2 Мбита/с</td>
	<td>400</td>
	<td>591</td>
</tr><tr>
	<td>Средно време на четене</td>
	<td>8.5 ms</td>
	<td>-</td>
	<td>9 ms</td>
	<td>8.9</td>
	<td>8.9</td>
</tr><tr>
	<td>Интерфейс</td>
	<td>Ultra-ATA/100</td>
	<td>Ultra-ATA/133</td>
	<td>Ultra-ATA/100</td>
	<td>Ultra-ATA/100</td>
	<td>Ultra-ATA/100</td>
</tr>
<tr>
	<td>Скорост на 'буфер- контролер' данните</td>
	<td>100 Мбайта/с</td>
	<td>133 Мбайта/с</td>
	<td>100 Мбайта/с</td>
	<td>-</td>
	<td>-</td>
</tr>
<tr>
	<td>Обем на буфера</td>
	<td>2 MB</td>
	<td>2 MB</td>
	<td>2 MB</td>
	<td>2 MB</td>
	<td>8 MB</td>
</tr>
</table>


## SMART
S.M.A.R.T. е акроним от Self-Monitoring, Analysis and Reporting Technology т.е. технология за самонаблюдение, анализ и известяване.
S.M.A.R.T. е индустриален стандарт за мониторинг и известяване на грешки в периферните устройства. Целта на технологията е да намали риска от загуба на данни.
Следи се състоянието на електромоторите, плочите, главите и електрониката на устройството.

## Automatic Acoustic Management
Възможност за намаляване на шума от диска чрез регулиране на скоростта на позициониране на рамото на главата. По ниските нива на шум костват няколко милисекунди повече

## Резултати

<table width="100%" border="1" cellspacing="0" cellpadding="2">
<tr>
	<td></td>
	<td>Средно време за достъп (ms)</td>
	<td>Четене с буфер (MB/s)</td>
	<td>Последователно четене (MB/s)</td>
	<td>Случайно четене (MB/s)</td>
</tr>
<tr>
	<td>ExcelStor J340</td>
	<td>12.3</td>
	<td>25.5</td>
	<td>25.4</td>
	<td>25.1</td>
</tr>
<tr>
	<td>Maxtor6E040L0</td>
	<td>14.1</td>
	<td>25.3</td>
	<td>24.6</td>
	<td>24.5</td>
</tr>
<tr>
	<td>ST340014A</td>
	<td>14.9</td>
	<td>25.2</td>
	<td>20.6</td>
	<td>20.2</td>
</tr>
<tr>
	<td>WD400BB</td>
	<td>15.2</td>
	<td>23.6</td>
	<td>21.5</td>
	<td>21</td>
</tr>
<tr>
	<td>WD400JB</td>
	<td>15</td>
	<td>25.4</td>
	<td>24.1</td>
	<td>23.7</td>
</tr>
</table>

За мое голямо учудване, ExcelStor J340 се представи най-добре по всички тествани указатели. Може би това се дължи на факта че моделът е сравнително нов и в него са залегнали технологии използвани в по-високите класове на другите производители. И все пак изборът си остава ваш :)

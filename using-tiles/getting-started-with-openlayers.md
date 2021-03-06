---
layout: docs
title: Використання OpenLayers
permalink: /using-tiles/getting-started-with-openlayers/
---

## Вступ

[OpenLayers](http://openlayers.org/)&nbsp;– це багатофункціональна бібліотека JavaScript для показу мап. Вона розповсюджується на умовах дозвільної Ліцензії BSD для коду з відкритими сирцями, тож її можна використовувати на будь-якому сайті без побоювань порушення юридичних норм. Сирці бібліотеки доступні на [GitHub](https://github.com/openlayers/ol3/).

Тут, ми обмежимо себе невеличким самодостатнім прикладом, що демострує можливості бібліотеки. Радимо ознайомитись з детальними [прикладами](http://openlayers.org/en/latest/examples/) та [описом API](http://openlayers.org/en/latest/apidoc/) з офіційного сайту для детальнішого опрацювання.

## Початок роботи

Перенесіть наступний код у файл, наприклад `openlayers.html`, і відкрийте його у вашому веб-оглядачі або перейдіть за посиланням щоб відкрити файл [openlayers.html]({{site.baseurl}}/assets/openlayers.html):

{% highlight html %}
{% include openlayers.html %}
{% endhighlight %}

Докладні пояснення щодо коду дивіться на офіційному сайті. [^1]

# Додаткові посилання
Якщо ви бажаєте:

*   використовувати інше тло?&nbsp;→ Openlayers має підтримку [TMS](https://en.wikipedia.org/wiki/Tile_Map_Service) та [WMS](https://uk.wikipedia.org/wiki/Web_Map_Service). Ознайомтесь з [прикладами](http://openlayers.org/en/latest/examples/) з офіційного сайту Openlayers та [документацією до API](http://openlayers.org/en/latest/apidoc/), щоб дізнатись про наявні можливості.
*   додати розташування всіх офісів вашої компанії?&nbsp;→ Збережіть координати у файл [GeoJSON](http://geojson.org/) та [додайте їх](http://openlayers.org/en/latest/examples/select-features.html) на мапу.
*   використовувати іншу картографічну проєкцію?&nbsp;→ OpenLayers підтримує всі проєкції Proj4 у разі використання JavaScript бібліотеки [proj4js](http://proj4js.org/). Крім того, підтримується [зміна проєкції на стороні клієнта](http://openlayers.org/en/latest/examples/reprojection-by-code.html) для растрових тайлів, тож ви можете використовувати тайли з OpenStreetMap у вашій власній проєкції.

----
[^1]: Швидкий старт&nbsp;– <https://openlayers.org/en/latest/doc/quickstart.html>

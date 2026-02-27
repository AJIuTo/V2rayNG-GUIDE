<h1>V2rayNG-GUIDE</h1>

<p>Инструкция по настройке приложения на телефоне.</p>

<h2>V2rayNG</h2>

<div style="display: flex; flex-wrap: wrap; gap: 20px; justify-content: center;">
  <!-- Карточка 1 -->
  <div style="width: 300px; text-align: center;">
    <img src="images/photo_1_y.jpg" alt="Фото 1" style="width: 40%; border-radius: 8px;">
    <p style="margin-top: 8px; font-style: italic;">Нажимаем на 3 точки на главном экране как на картинке. Предварительно надо скопировать текст своей конфигурации</p>
  </div>
  <!-- Карточка 2 -->
  <div style="width: 300px; text-align: center;">
    <img src="images/photo_2_y.jpg" alt="Фото 2" style="width: 40%; border-radius: 8px;">
    <p style="margin-top: 8px; font-style: italic;">Импортируем из буфера обмена</p>
  </div>
  <!-- Карточка 3 -->
  <div style="width: 300px; text-align: center;">
    <img src="images/photo_3_y.jpg" alt="Фото 3" style="width: 40%; border-radius: 8px;">
    <p style="margin-top: 8px; font-style: italic;">Жмем на 3 полоски слева сверху</p>
  </div>
  <!-- Карточка 4 -->
  <div style="width: 300px; text-align: center;">
    <img src="images/photo_4_y.jpg" alt="Фото 4" style="width: 40%; border-radius: 8px;">
    <p style="margin-top: 8px; font-style: italic;">Файлы ресурсов</p>
  </div>
  <!-- Карточка 5 -->
  <div style="width: 300px; text-align: center;">
    <img src="images/photo_5_y.jpg" alt="Фото 5" style="width: 40%; border-radius: 8px;">
    <p style="margin-top: 8px; font-style: italic;">Сначала источник выбираем как на картинке, потом жмем на облако для обновления файлов</p>
  </div>
  <!-- Карточка 6 -->
  <div style="width: 300px; text-align: center;">
    <img src="images/photo_6_y.jpg" alt="Фото 6" style="width: 40%; border-radius: 8px;">
    <p style="margin-top: 8px; font-style: italic;">Возвращаемся в меню и жмем маршрутизация. Копируем текст :</p>
	<pre style="background: #2d2d2d; color: #f8f8f2; padding: 12px; border-radius: 6px; overflow-x: auto; font-size: 14px;"><code>
[{"domain":["geosite:category-ads-all"],"enabled":false,"looked":false,"outboundTag":"block","remarks":"RU-1 [Блокировка рекламы]"},{"enabled":false,"ip":["geoip:private"],"looked":false,"outboundTag":"direct","remarks":"RU-1 [Приватные сети напрямую]"},{"domain":["geosite:private"],"enabled":false,"looked":false,"outboundTag":"direct","remarks":"RU-1 [Приватные домены напрямую]"},{"enabled":false,"looked":false,"outboundTag":"proxy","port":"0-65535","remarks":"RU-1 [Остальное в прокси]"},{"enabled":false,"looked":false,"outboundTag":"direct","protocol":["bittorrent"],"remarks":"RU-2 [Торрент напрямую]"},{"domain":["geosite:category-ads-all"],"enabled":false,"looked":false,"outboundTag":"block","remarks":"RU-2 [Блокировка рекламы]"},{"enabled":false,"ip":["geoip:private"],"looked":false,"outboundTag":"direct","remarks":"RU-2 [Приватные сети напрямую]"},{"domain":["geosite:private"],"enabled":false,"looked":false,"outboundTag":"direct","remarks":"RU-2 [Приватные домены напрямую]"},{"enabled":false,"ip":["geoip:ru"],"looked":false,"outboundTag":"direct","remarks":"RU-2 [Доступные только в России напрямую]"},{"enabled":false,"looked":false,"outboundTag":"proxy","port":"0-65535","remarks":"RU-2 [Остальное в прокси]"},{"enabled":false,"looked":false,"outboundTag":"direct","protocol":["bittorrent"],"remarks":"RU-3 [Торрент напрямую]"},{"domain":["geosite:category-ads-all"],"enabled":false,"looked":false,"outboundTag":"block","remarks":"RU-3 [Блокировка рекламы]"},{"enabled":false,"ip":["geoip:private"],"looked":false,"outboundTag":"direct","remarks":"RU-3 [Приватные сети напрямую]"},{"domain":["geosite:private"],"enabled":false,"looked":false,"outboundTag":"direct","remarks":"RU-3 [Приватные домены напрямую]"},{"enabled":false,"ip":["1.0.0.1","1.1.1.1","8.8.8.8","8.8.4.4"],"looked":false,"outboundTag":"proxy","remarks":"RU-3 [DNS в прокси]"},{"enabled":false,"looked":false,"network":"udp","outboundTag":"proxy","port":"50000-65535","remarks":"RU-3 [Дискорд (Голосовой) в прокси]"},{"enabled":false,"ip":["geoip:ru-blocked"],"looked":false,"outboundTag":"proxy","remarks":"RU-3 [Заблокированные сети в прокси]"},{"domain":["geosite:ru-blocked"],"enabled":false,"looked":false,"outboundTag":"proxy","remarks":"RU-3 [Заблокированные домены в прокси]"},{"enabled":false,"looked":false,"outboundTag":"direct","port":"0-65535","remarks":"RU-3 [Остальное напрямую]"}]
</code></pre>
  </div>
  <!-- Карточка 7 -->
  <div style="width: 300px; text-align: center;">
    <img src="images/photo_7_y.jpg" alt="Фото 7" style="width: 40%; border-radius: 8px;">
    <p style="margin-top: 8px; font-style: italic;">Сначала стратегию выбираем как на картинке, затем жмем на 3 точки</p>
  </div>
  <!-- Карточка 8 -->
  <div style="width: 300px; text-align: center;">
    <img src="images/photo_8_y.jpg" alt="Фото 8" style="width: 40%; border-radius: 8px;">
    <p style="margin-top: 8px; font-style: italic;">Импортируем. Выбрием все поля с RU-3</p>
  </div>
</div>

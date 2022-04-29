# Неисправности в работе

### Как правильно поставить код?

Код необходимо установить в `<head>` вашего сайта. Кроме статичных баннеров- их мы устанавливаем в место отображения.

Код на странице можно использовать только один раз. При дублировании кода и одновременном запросе откроется только один рекламный блок. Это связанно с тех. ограничениями аукциона.

На нескольких сайтах нельзя размещать один и тот же код.

Пример кода:

`(function(w, d, n, s, t) {w[n] = w[n] || [];w[n].push(function() {mp_banners('4537');});t = d.getElementsByTagName("script")[0];s = d.createElement("script");s.type = "text/javascript";s.src = "https://mpsuadv.ru/lib/custom/banners.js";s.async = true;t.parentNode.insertBefore(s, t);})(this, this.document, "mpsuRotator");`

### Как проверить работу Full-Screen минуя настройки отображения (capping)

Для этого в конце ссылки добавьте параметр **`?mp_no_capping`**

Пример : https://mysite.com/**`?mp_no_capping`**

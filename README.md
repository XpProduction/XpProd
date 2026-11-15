# XPprod — сборка для корневого GitHub Pages сайта

Эта сборка настроена для адреса **https://xpproduction.github.io/** — без `/XpProd/`.

## 1. Создайте специальный репозиторий

Старый репозиторий `XpProd` не удаляйте. Войдите на GitHub под аккаунтом `XpProduction`, откройте https://github.com/new, введите в **Repository name** точно `xpproduction.github.io`, выберите **Public**, не добавляйте README/license/.gitignore, затем нажмите **Create repository**.

Это специальное имя GitHub Pages для личного сайта; официальный гайд: https://docs.github.com/en/pages/quickstart

## 2. Загрузите сайт в корень нового репозитория

1. Распакуйте архив; загружать ZIP целиком не нужно.
2. В новом репозитории выберите **Add file → Upload files**.
3. Загрузите всё содержимое распакованной папки. Важно: `index.html`, `robots.txt`, `sitemap.xml`, `yandex_7fbe98f5a7d13bfa.html`, `google28955018109b2e22.html` должны лежать прямо в корне репозитория. Не кладите их во вложенную папку. Папку `assets` загружайте целиком вместе с `thumbs`.
4. Нажмите **Commit changes**.

## 3. Включите GitHub Pages

В репозитории откройте **Settings → Pages**. В **Build and deployment** выберите **Deploy from a branch**; для Branch выберите `main`, папку `/(root)` и нажмите **Save**. Дождитесь зелёной галочки у Pages deployment во вкладке **Actions**, затем откройте https://xpproduction.github.io/ .

## 4. Подтвердите сайт в Яндекс Вебмастере

Добавьте как сайт ровно `https://xpproduction.github.io/` (не `/XpProd/`). Выберите подтверждение через HTML-файл; файл `yandex_7fbe98f5a7d13bfa.html` уже лежит в корне этой сборки. После публикации откройте https://xpproduction.github.io/yandex_7fbe98f5a7d13bfa.html — должна появиться строка `Verification: 7fbe98f5a7d13bfa`, не 404. Вернитесь в Вебмастер и нажмите **Проверить**. Google verification file тоже приложен, если понадобится.

После подтверждения Яндекса отправьте в **Индексирование → Файлы Sitemap** адрес `https://xpproduction.github.io/sitemap.xml`. В этой версии `robots.txt`, sitemap, canonical, Open Graph, JSON-LD и webmanifest уже используют корневой адрес.

## Что сохранено в этой сборке

Android-оптимизация, исходный desktop-дизайн, SEO, аватар сайта и превью всех **31 видео** (включая Standard). Превью остаются, загружаются лениво; видеоплеер включается по нажатию.

Обновлена иконка сайта (SVG/PNG/ICO/Apple touch) на основе присланной картинки XP; параметры `?v=4` сбрасывают кэш старой иконки в браузере.

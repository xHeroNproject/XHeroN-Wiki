# Быстрый запуск через GitHub Desktop

## 1. Подготовка

Установите GitHub Desktop и войдите в свой аккаунт GitHub.

## 2. Создание локального репозитория

1. Распакуйте эту папку, например в `X:\X Hero Project\13_Website_Release\XHeroN-Wiki`.
2. Откройте GitHub Desktop.
3. Выберите **File → Add local repository**.
4. Укажите распакованную папку.
5. Если программа сообщает, что это ещё не Git-репозиторий, выберите создание репозитория в этой папке.
6. Commit summary: `X Hero N Wiki v1.0`.
7. Нажмите **Commit to main**.
8. Нажмите **Publish repository**.

Рекомендуемые параметры:

- Name: `XHeroN-Wiki`
- Description: `Энциклопедия карты X Hero N 10.8 для Warcraft III`
- Репозиторий: **Public**

## 3. Включение сайта

На GitHub откройте репозиторий:

**Settings → Pages → Build and deployment → Deploy from a branch**

Выберите:

- Branch: `main`
- Folder: `/(root)`

Нажмите **Save**.

## 4. Адрес сайта

Обычно сайт появится по адресу:

`https://ВАШ-ЛОГИН.github.io/XHeroN-Wiki/`

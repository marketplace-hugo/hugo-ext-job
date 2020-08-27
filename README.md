# Information / Информация

Тип контента **Вакансия**.

- `title` - заголовок вакансии.
- `description` - описание вакансии.
- `cover` - обложка вакансии.
  - `url` - адрес обложки.
  - `position-x` - позиция обложки по оси X.
  - `position-y` - позиция обложки по оси Y.
- `icon` - иконка вакансии.
- `job` - информация о вакансии.
  - `position` - должность.
  - `department` - отдел.
  - `education` - образование.
  - `salary` - информация по окладу.
    - `currency` - валюта.
    - `value` - размер оклада.
    - `minValue` - минимальный размер оклада.
    - `maxValue` - максимальный размер оклада.
    - `unitText` - единица измерения оклада (`HOUR`, `DAY`, `WEEK`, `MONTH`, `YEAR`).
- `date` - дата публикации вакансии.
- `expiryDate` - дата истечения публикации вакансии.

## Install / Установка

```
git submodule add https://gitlab.com/marketplace-hugo/hugo-ext-job.git archetypes/job
```

## Update / Обновление

```
git submodule update --remote
```

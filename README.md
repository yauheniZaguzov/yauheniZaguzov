### Hi there 👋

<!--
**yauheniZaguzov/yauheniZaguzov** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on BRT company
- 🌱 I’m currently learning TRUT
schedule: # Run workflow automatically
    - cron: '0 * * * *' # Runs every hour, on the hour
  workflow_dispatch: # Run workflow manually (without waiting for the cron to be called), through the GitHub Actions Workflow page directly

jobs:
  update-readme-with-blog:
    name: Update this repo's README with latest blog posts
    runs-on: ubuntu-latest
    steps:
      - name: Checkout
        uses: actions/checkout@v2
      - name: Pull in dev.to posts
        uses: gautamkrishnar/blog-post-workflow@v1
        with:
          feed_list: "https://dev.to/feed/gautamkrishnar,https://www.gautamkrishnar.com/feed/"
5. Заменить приведенный выше список URL-адресов собственными адресами. Для этого будет полезна ссылка, перейдя по которой, вы найдете необходимые ссылки для подгрузки ваших постов из популярных источников: Youtube, Medium, Reddit, Dev.to, Wordpress и т.д.

Популярные места для блогов

6. Теперь нужно коммитнуть изменения и подождать, пока код отработает, либо же запустить его в ручную.

Для того чтобы узнать, как это сделать, лучше всего посмотреть сегмент в данном видео, в нем мы проходим по каждому из вышеперечисленных шагов и меняем все необходимое.

Также информация на английском языке из уст автора: https://github.com/gautamkrishnar/blog-post-workflow

Как отобразить статистику GitHub профиля
Напоследок, осталось разобраться с выводом статистики в GitHub Profile Readme. Для этого мы воспользуемся следующим репозиторием: https://github.com/anuraghazra/github-readme-stats

Добавление статистики профиля может быть произведено всего одной строчкой кода:

[![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=alexeyshpavda)](https://github.com/anuraghazra/github-readme-stats)
Единственное, что нужно сделать - это указать в ?username= имя вашего пользователя.

Статистика профиля на GitHub

Для настройки и стилизации бейджа со статистикой рекомендуется перейти в вышеуказанный репозиторий и найти необходимые вам настройки.

Полезные ссылки:

Профиль на GitHub: https://github.com/AlexeyShpavda
Иконки: https://simpleicons.org
Бейджи: https://shields.io
Workflow: https://github.com/gautamkrishnar/blog-post-workflow
Полезное дополнение к Worflow: https://en.wikipedia.org/wiki/Cron 
Stats: https://github.com/anuraghazra/github-readme-stats

Телеграм: https://t.me/the_cybermania
Видео: https://www.youtube.com/watch?v=1yELlB39TvY



GitHub
README.md
GitHub Profile Readme
Как создать GitHub Profile Readme
Как добавить Profile Readme в Профиль
Как оформить профиль на GitHub
Статистика GitHub профиля


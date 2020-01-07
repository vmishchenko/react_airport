# React Airport

## Task

(Задачу взято з Dev Challenge Frontent)

Створити на React табло прильотів / вильотів з аеропорту Жуляни: [https://iev.aero/en/departures](https://iev.aero/en/departures). Додаток має повторювати функціонал і UI аеропорту. Копіювати стилі напряму з існуючого сайту
заборонено.

Зчитувати дані слід через API: https://api.iev.aero/api/flights/13-06-2019 (динамічно, підставивши поточну дату).

Необхідний функціонал:
- відображати дві закладки Arrivals / Departures
- відображати дані для кожної закладки:
  - Terminal
  - Gate (якщо інформація присутня в API)
  - Time
  - Destination
  - Airline (без логотипу авіалінії)
  - Flight #
  - Status

За бажання можна додати більше функціоналу.

## Workflow

- Fork the repository with task
- Clone forked repository
    ```bash
    git clone git@github.com:<user_name>>/<task_repository>.git
    ```
- Run `npm install` to install dependencies.
- Then develop

## Development mode

- Run `npm run start` to start `http-server` on `http://localhost:3000`
    When you run server the command line window will no longer be available for
    writing commands until you stop server (`ctrl + c`). All other commands you
    need to run in new command line window.
- Follow [HTML, CSS styleguide](https://mate-academy.github.io/style-guides/htmlcss.html)
- Follow [the simplified JS styleguide](https://mate-academy.github.io/style-guides/javascript-standard-modified)
- When you finished `Deploy on gh-pages`

## Deploy on gh-pages

- Build the project
  ```bash
  $ npm run build
  ```
- Commit and push all recent changes
  ```bash
  $ git add .
  $ git commit -m 'commit message'
  $ git push origin master
  ```
- Execute `npm run deploy`. This command will push the `/build` folder to branch
  `gh-pages` in your remote repository.
- Add links to your demo in readme.md.
  - `[DEMO LINK](https://<your_account>.github.io/<repo_name>/)` - this will be a
  link to your index.html
- Commit and push all recent changes again.
- Create `Pull Request` from forked repo `(<branch_name>)` to original repo
(`master`).
- Add a link at `PR` to Google Spreadsheets.

## Project structure

- `src/` - directory for css, js, image, fonts files
- `build/` - directory for built pages

You should be writing code in `src/` directory.

### Demo link

Add link here: `[DEMO LINK](https://vmishchenko.github.io/react_airport)`
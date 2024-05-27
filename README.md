### Flask Application Design: News Articles App

#### HTML Files

- `index.html`: This file will serve as the main page of the application. It will display a list of recent news articles, with each article containing its title, a brief description, and a link to the full article.

#### Routes

- `/`: This route will handle requests for the main page of the application. It will render the `index.html` file, passing in the list of recent news articles.
- `/article/<article_id>`: This route will handle requests for a specific news article. It will render the `article.html` file, passing in the details of the requested article.
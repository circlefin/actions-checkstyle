# actions-checkstyle

Runs checkstyle using reviewdog on pull requests.

This configuration is based on https://github.com/nikitasavinov/checkstyle-action, the only difference is that we package our own checkstyle.xml so that it's centrally defined and can be used in all of our repositories.

### IntelliJ Integration
See [the IntelliJ Integration README.](idea/)
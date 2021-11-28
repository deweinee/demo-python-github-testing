# Demo: testing github.com

### Selenium, pytest 

-----

Some of the tests require an actual password for my test github account. That password was removed from config/settings.py before pushing it to a public repository, for obvious reasons. In order for those tests not to fail skipif mark was added so only tests that don't require private credentials would run.

-----

Для прохождения некоторых тестов требуется пароль от тестового аккаунта github. Этот пароль был убран из config/settings.py перед выкладыванием в публичный репозиторий. Чтобы такие тесты не падали зря, для них добавлена метка skipif: с отсутствием пароля запущены будут только тесты, не требующие его.

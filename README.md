It's a simple docker setup to set up `Laravel` environment on local machine with `docker`.

### To run the local dev environment:
1. Place projects files into your `Laravel` project, navigate to `root` project folder.
2. Update `.env.example` and set database connection section:
   `DB_CONNECTION=mysql`
   `DB_HOST=mysql`
   `DB_PORT=3306`
   `DB_DATABASE=laravel`
   `DB_USERNAME=root`
   `DB_PASSWORD=root`
3. Run `make install`
   It will install composer dependencies, run migration, seeders, run tests
4. Open `http://localhost` for the `Laravel Welcome` page.

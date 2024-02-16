It's a simple docker setup to set up `Laravel` environment on local machine with `docker`.

### To run the local dev environment:
1. Place projects files into your `Laravel` project, navigate to `root` project folder.

2. Update `.env.example` and set database connection section:<br/>
   `DB_CONNECTION=mysql`<br/>
   `DB_HOST=mysql`<br/>
   `DB_PORT=3306`<br/>
   `DB_DATABASE=laravel`<br/>
   `DB_USERNAME=root`<br/>
   `DB_PASSWORD=root`<br/>

3. Run `make install`
   It will copy `.env.example` to `.env`, install composer dependencies, run migration, seeders, run tests
4. Open `http://localhost` for the `Laravel Welcome` page.

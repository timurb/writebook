# Writebook composer

This is a `docker-compose.yml` to run [Writebook](https://once.com/writebook) of https://37signals.com/

It is intended for educational purposes and is not recommended for any kind of production for the following reasons:
- HTTPS is disabled
- Important production fixes could be missing
- No idea if automatic updates are working
- Absolutely no testing was done. Use it on your own risk

## Usage

1. Download Writebook zip file provided to you upon registering at https://once.com/writebook
2. Unpack zip file to this git repository (be mindful of not committing the files to it)
3. Edit `.env` and put env vars of `RAILS_MASTER_KEY` and `SECRET_KEY_BASE` to it. Consult with Rails docs on the meaning.
4. Run
```
docker-compose up
```
5. Access it at http://localhost
6. If you like the application go use the installation command provided to you by upstream


## License and authors
* License:: MIT
* Author:: Timur Batyrshin <timurb@hey.com>

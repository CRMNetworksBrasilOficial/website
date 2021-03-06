# RailsInstaller Web

![Codeship Status](https://www.codeship.io/projects/cda693e0-f3e1-0130-c6a1-6e039e15cc73/status)

Web application for http://railsinstaller.org

### Contributing

Fork repository, make required changes, test, open a pull request on GitHub.

If you'd like to translate the site into a different locale, add the relevant
YAML file with translated strings to `config/locales` and make sure everything
works properly. Check out `config/locales/en.yml` for strings to localize.

#### Current Translations

- English (en)
- Brazilian portuguese (pt-BR)
- Russian (ru-RU)
- French - France (fr-FR)

### Testing

```bash
cp config/database.yml.template config/database.yml
bundle install --without="production test"
rails s
```

And visit http://localhost:3000

### Updating contributor list

```bash
rake update:contributors
```

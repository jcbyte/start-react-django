# start-react-django

Python script to automate the creation of web apps with react frontend and django backend.

## Usage

`start-react-django [-h] [-env NAME] [-ts] [-cors] name`

The command is available once the start-react-django module has been installed:

```bash
pip install git+https://github.com/jcbyte/start-react-django.git
```

## Django & React

### React

**Note:** These commands should be run from within `$PROJNAME$\frontend\`.

Once the project has been created the React web app can be compiled whilst watching for changes:

```bash
npm run dev
```

Compile a production build:

```bash
npm run build
```

### Django

**Note:** These commands should be run from within `$PROJNAME$\`.

To serve the app and start the Django server:

```bash
python manage.py runserver
```

## Licence

[Apache License 2.0](LICENSE)

# Wiki Project

A Wikipedia-like online encyclopedia built with Django. This project allows users to view, create, and edit encyclopedia entries.

## Features

- Browse all available encyclopedia entries
- View detailed content of each entry
- Search for specific entries
- Create new encyclopedia entries
- Edit existing entries
- Random page navigation

## Tech Stack

- Python
- Django
- HTML/CSS
- Markdown (for entry content)

## Installation

1. Clone the repository
   ```
   git clone https://github.com/rahul-004x/wiki-encyclopedia.git
   cd wiki
   ```

2. Install dependencies
   ```
   pip install -r requirements.txt
   ```

3. Run migrations
   ```
   python manage.py migrate
   ```

4. Start the development server
   ```
   python manage.py runserver
   ```

5. Open your browser and navigate to `http://127.0.0.1:8000/`

## Usage

- **Home Page**: See a list of all encyclopedia entries
- **Entry Page**: View the contents of an entry by clicking on its title
- **Search**: Use the search bar to find entries
- **Create New Page**: Add new encyclopedia entries
- **Edit Page**: Modify existing entries
- **Random Page**: Navigate to a random encyclopedia entry

## Project Structure

```
wiki/
├── encyclopedia/
│   ├── static/
│   │   └── encyclopedia/
│   │       └── styles.css
│   ├── templates/
│   │   └── encyclopedia/
│   │       ├── index.html
│   │       └── layout.html
│   ├── util.py
│   ├── views.py
│   ├── urls.py
│   └── models.py
├── entries/
│   └── [Markdown files for wiki entries]
└── wiki/
    ├── settings.py
    ├── urls.py
    └── wsgi.py
```

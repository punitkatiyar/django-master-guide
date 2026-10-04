# Django Templates

```
Django Templates
│
├── Template Syntax
│   ├── {{ variable }}
│   ├── {% tag %}
│   └── {# comment #}
│
├── Variables
│   └── {{ name }}
│
├── Tags
│   ├── if
│   ├── for
│   ├── extends
│   ├── block
│   ├── include
│   └── load
│
├── Filters
│   ├── upper
│   ├── lower
│   ├── title
│   ├── length
│   ├── default
│   └── truncatechars
│
├── Template Inheritance
│   ├── extends
│   └── block
│
├── Reusable Components
│   └── include
│
└── Customization
    ├── Custom Filters
    └── Custom Tags


Static Files
│
├── CSS
├── JavaScript
├── Images
├── STATIC_URL
├── STATICFILES_DIRS
└── collectstatic

```

| Syntax | Purpose | Example |
|---|---|---|
| `{{ }}` | Display data | `{{ name }}` |
| `{% %}` | Execute template logic | `{% if user %}` |
| `{# #}` | Comment | `{# comment #}` |
| `{% load %}` | Load custom/template libraries | `{% load static %}` |

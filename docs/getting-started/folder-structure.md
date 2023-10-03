---
sidebar_position: 2
---

# Folder structure

Boilerplate folder structure:

```
website # root directory of your site
├── public
├── src
│   ├── features
│   |   ├── login
│   |   |   ├── hooks
│   |   |   ├── types
│   |   |   └── ui
│   |   |       ├── components
│   |   |       └── SectionData.tsx
│   |   ├── register
│   |   |   └── ...
│   |   ├── users
│   |   |   └── ...
│   |   └── [feature_name]
│   |       └── ...
│   ├── pages
│   |   ├── auth
|   |   |   ├── login
|   |   |   |   └── index.tsx
|   |   |   └── register
|   |   |       └── index.tsx
|   |   ├── users
|   |   |   └── index.tsx
|   |   └── [feature_name]
|   |       └── index.tsx
│   └── shared
|       ├── api
|       ├── components
|       ├── constants
|       ├── font
|       ├── hooks
|       ├── images
|       ├── lib
|       ├── styles
|       ├── types
|       └── utils
├── next.config.js
├── ...
.
```

selengkapnya [`/src` Directory](/category/sourcesrc-directory).
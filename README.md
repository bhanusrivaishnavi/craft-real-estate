# craft-real-estate

A small Craft CMS site ("Olivia / House Quest" demo) — built from a Craft CMS starter project and configured for local development with DDEV.

## Quick summary
- PHP / Craft project with public `web/` folder.
- Project uses DDEV for local development (see `.ddev/config.yaml`).
- Templates reference static frontend assets under `/assets/` and images under `/images/`.

## Requirements
- Docker installed and running
- DDEV installed and configured (https://ddev.com/)
- Composer 

## Local development 
1. Start DDEV in the project root (where `.ddev/` lives): ddev start

2. Install PHP dependencies (if needed): ddev composer install
   
4. Open the site URL shown by ddev:

```
https://craft-real-estate.ddev.site
```

4. Use the Craft control panel (https://craft-real-estate.ddev.site/admin) to inspect asset volumes and uploaded files.

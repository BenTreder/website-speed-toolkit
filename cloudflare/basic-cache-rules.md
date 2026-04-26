# Basic Cloudflare Cache Rules

## Cache Longer

Good targets:

```txt
/assets/*
/images/*
/img/*
/css/*
/js/*
/fonts/*
```

## Avoid Aggressive Caching

```txt
/admin/*
/login/*
/checkout/*
/cart/*
/account/*
/wp-admin/*
/wp-login.php
```

## Recommended

- Cache static assets longer
- Bypass admin pages
- Bypass login pages
- Test after changes

# Quantumult X Rewrites

A collection of Quantumult X rewrite rules and scripts.

## Structure

```
├── plex/
│   ├── plex-username.conf   # Rewrite config for Plex username
│   └── plex-username.js     # Response body rewrite script
```

## Usage

### Plex Username Rewrite

Modify the displayed username in the Plex app.

**Remote import:**

```
https://raw.githubusercontent.com/liunice/quantumult-x-rewrites/main/plex/plex-username.conf
```

Add the above URL in Quantumult X: Settings -> Rewrite -> Import.

**Note:** Make sure MITM is enabled and the CA certificate is installed and trusted.

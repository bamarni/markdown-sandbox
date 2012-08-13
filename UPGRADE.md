# UPGRADE INSTRUCTIONS

## CACHING

### Changed Storage class API

The method name for fetching in Cache\Storage class has changed:

Before:
```
$storage->fetch('key');
```

Now:
```
$storage->get('key');
```

## TEMPLATING

...
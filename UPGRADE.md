# UPGRADE INSTRUCTIONS

## CACHING

### Changed Storage class API
The method name for fetching in Cache\Storage class has changed:
Before:
```php
$storage->fetch('key');
```
Now:
```php
$storage->get('key');
```
## TEMPLATING

...
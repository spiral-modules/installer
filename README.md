# Spiral Application installer

![Installer](https://user-images.githubusercontent.com/773481/208850084-891a9d6f-3e70-4a06-af57-4e63c37c9c47.png)

Spiral Framework is a High-Performance PHP/Go Full-Stack framework and group of over sixty PSR-compatible components. The Framework execution model based on a hybrid runtime where some services (GRPC, Queue, WebSockets, etc.) handled by Application Server [RoadRunner](https://github.com/roadrunner-server/roadrunner) and the PHP code of your application stays in memory permanently (anti-memory leak tools included).

[App Skeleton](https://github.com/spiral/app) | [**Documentation**](https://spiral.dev/docs) | [Discord](https://discord.gg/TFeEmCs) | [Twitter](https://twitter.com/spiralphp) | [CHANGELOG](/CHANGELOG.md) | [Contributing](https://github.com/spiral/guide/blob/master/contributing.md)

<br/>

## Server Requirements

Make sure that your server is configured with following PHP version and extensions:
* PHP 8.1+, 64bit
* *mb-string* extension
* PDO Extension with desired database drivers



## Installation

```bash
composer create-project spiral/installer
```

> Application server will be downloaded automatically (`php-curl` and `php-zip` required).

To start application server execute:

```bash
./rr serve
```

Application will be available on `http://localhost:8080`.

> Read more about application server configuration [here](https://roadrunner.dev/docs).

## License:

MIT License (MIT). Please see [`LICENSE`](./LICENSE) for more information. Maintained by [Spiral Scout](https://spiralscout.com).

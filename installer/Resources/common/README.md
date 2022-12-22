# :app_name

[**Documentation**](https://spiral.dev/docs) | [Discord](https://discord.gg/TFeEmCs) | [Twitter](https://twitter.com/spiralphp) | [Contributing](https://spiral.dev/docs/about-contributing/)

## About Spiral Framework

Spiral Framework is a High-Performance Long-Living Full-Stack framework and group of over sixty PSR-compatible
components. The Framework execution model based on a hybrid runtime where some services (GRPC, Queue, WebSockets, etc.)
handled by RoadRunner application server and the PHP code of your application stays in memory permanently (anti-memory
leak tools included).

## Server Requirements

Make sure that your server is configured with following PHP version and extensions:

* PHP 8.1+, 64bit
* [mb-string](https://www.php.net/manual/en/intro.mbstring.php) extension

:next_steps

<br />

After the project has been created and installed, start RoadRunner server using the following command:

```bash
./rr serve
```

<br />

Once you have started RoadRunner server, your application will be accessible in your web browser at `http://localhost:8080`.

## Console commands

### Download or update RoadRunner

Allows to install the latest version of the RoadRunner compatible with your environment (operating system, processor
architecture, runtime, etc...).

```bash
composer rr:download
# or
./vendor/bin/rr get-binary
```

### Download or update protoc get GRPC plugin

Allows to install the latest version of the `protoc-gen-php-grpc` file compatible with your environment (operating
system, processor architecture, runtime, etc...).

```bash
composer rr:download-protoc
# or
./vendor/bin/rr download-protoc-binary
```

License
--------
MIT License (MIT). Please see [`LICENSE`](./LICENSE) for more information. Maintained by [Spiral Scout](https://spiralscout.com).

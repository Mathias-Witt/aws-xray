# Change Log

## 1.1.0 - 2019-01-24

- Use `register_shutdown_function` to capture fatal errors
- Update file loading and organization to allow loading early in the boot process. `inc/namespace.php` is to be loaded first, then `plugin.php` when WordPress is loaded.

## 1.0.3 - 2018-10-23

- Use local declaration of wp_debug_backtrace_summary

## 1.0.2 - 2018-10-12

- Track Remote Requests made via the WordPress HTTP API.

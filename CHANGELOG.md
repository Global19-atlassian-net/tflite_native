# 0.4.1

* Updated the documentation of this package to clarify that is is discontinued.

# 0.4.0+1

* Removed the dependency on quiver.

# 0.4.0

* Replaced uses of deprecated `asExternalTypedData` with `asTypedList`.
* Updated to use Dart 2.6 and latest dart:ffi APIs

# 0.3.0

* Update to new tflite C API

# 0.3.0

* Update to new tflite C API

# 0.2.3

* Specify `>=2.5.0` in `pubspec.yaml`

# 0.2.2

* Use `Pointer.asExternalTypedData` for reading output tensor

# 0.2.1

* Rebuild tflite shared libraries to include
  [tensorflow/tensorflow@4735b9b#diff-4e94df4d2961961ba5f69bbd666e0552](https://github.com/tensorflow/tensorflow/commit/4735b9bc02d35864eaba6ab48d73b73b333390e2#diff-4e94df4d2961961ba5f69bbd666e0552)

# 0.2.0

* Load shared object as sibling when running from snapshot

# 0.1.0

* Apply fixes from `dartfmt`
* Update package description

# 0.0.3

* Bundle binaries for 64-bit linux, mac, and windows systems
* Bindings for 24 / 29 functions exposed by libtensorflow_c.so

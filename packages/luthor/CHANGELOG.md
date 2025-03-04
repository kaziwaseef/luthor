## 0.2.2

 - **FIX**: redundant calls fromJson in SchemaValidationError.
 - **FIX**(luthor): SchemaValidation null error due to covariant.
 - **FIX**(luthor): l.list() does not validate inner values correctly.
 - **FEAT**(luthor): add fromJson argument to validateSchema.

## 0.2.1

 - **FIX**: redundant calls fromJson in SchemaValidationError.
 - **FIX**(luthor): SchemaValidation null error due to covariant.
 - **FIX**(luthor): l.list() does not validate inner values correctly.
 - **FEAT**(luthor): add fromJson argument to validateSchema.

# 0.2.0

- Upgrade minimum Dart SDK version to 3.0.0
- `validate` and `validateSchema` now return sealed classes instead of Freezed unions
- Add `fromJson` argument to `validateSchema` to allow for custom JSON deserialization
- Fix a bug where `l.list()` does not validated inner values correctly ([#33](https://github.com/exaby73/luthor/issues/33))
- Fix a bug where nested schemas throw a null error when the data is empty ([#41](https://github.com/exaby73/luthor/issues/41))

# 0.1.6

- Added better documentation and examples

# 0.1.5

- Fixed a bug where errors from previous validations are persisted

# 0.1.3

- Fixes with previous release

# 0.1.1

- Add support for validating emojis with `l.string().emoji()`
- Add support for validating uuids with `l.string().uuid()`
- Add support for validating cuids with `l.string().cuid()` and `l.string().cuid2()`
- Add support for validating regexs with `l.string().regex()` and `l.string().cuid2()`
- Add better errors

# 0.1.0

- (Breaking change) Migrate `ValidationResult` to freezed's union type for better type safety

# 0.0.2

- Add string validation for Uris
- Add list validation

# 0.0.1+2

- Export `Validator` and `StringValidator` classes

# 0.0.1+1

- Add more examples to README.md

# 0.0.1

- Initial release

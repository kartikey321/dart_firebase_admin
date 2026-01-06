# googleapis_auth_utils

This package contains extended functionality of the (googleapis_auth)[https://pub.dev/packages/googleapis_auth] to aide the Firebase Admin Dart SDK.

## Usage

Install the `googleapis_auth` and `googleapis_auth_utils` packages:

```bash
$ dart pub add googleapis_auth googleapis_auth_utils
```

Import the `googleapis_auth_utils` in your project:

```dart
import 'package:googleapis_auth_utils/googleapis_auth_utils.dart';
```

The existing `googleapis_auth` package will now have extended functionality:

```dart
final projectId = await authClient.getProjectId();
final credential = authClient.credential;
final encrypted = await authClient.sign('data-to-sign');
```

## Additional Functionality

1. Impersonated client
2. Crypto signer
3. Improved credential detection and support
4. Automated project ID detection 

## License

See [LICENSE](LICENSE).
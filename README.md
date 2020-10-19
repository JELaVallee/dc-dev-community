# dc_community_app

Flutter web application for the [DC Developer Community website](https://devcommunity.org/)

## Getting Started

Install flutter development environment for your system: https://flutter.dev/docs/get-started/install

Clone this repository in your local workspace:

```
[{workspace-root}]$ git clone https://github.com/devcommunity-org/dc-dev-community.git
```

In the project directory, build the application for web:

```
[{workspace-root}/dc-dev-community/]$ flutter build web
```

Run the application on a local development web server:

```
[{workspace-root}/dc-dev-community/]$ flutter run -d web-server
Launching lib/main.dart on Web Server in debug mode...
Syncing files to device Web Server...                                   
14,222ms (!)                                       
lib/main.dart is being served at http://localhost:33851
The web-server device requires the Dart Debug Chrome extension for debugging. Consider using the Chrome or Edge devices for an improved
development workflow.

Warning: Flutter's support for web development is not stable yet and hasn't
been thoroughly tested in production environments.
For more information see https://flutter.dev/web

🔥  To hot restart changes while running, press "r" or "R".
```

In your web browser (Chrome recommended) open the URL displayed in the startup output (e.g. "http://localhost:33851" in the example above)

## Learn More

Flutter for web is an exciting new capability of the flutter framework and still a "beta" capability. To learn more and get your development environment setup for Flutter web development and debugging check out the [Flutter Web Getting Started docs](https://flutter.dev/docs/get-started/web).

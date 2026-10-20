# Medical Services – MOI patient app — test builds

Test builds of the patient app mock. Source code is kept in a separate private repository; this
repository only distributes builds.

Each release has two files:

* **sfh-app-release.apk** — Android. Open the file on the phone and allow installs from unknown
  sources, or run `adb install sfh-app-release.apk`.
* **sfh-app-web.zip** — Web. Unzip, then serve the `web/` folder over HTTP, for example
  `cd web && python3 -m http.server 8080` and open http://localhost:8080. Flutter web does not run
  from a `file://` URL.

The app is a mock with sample data and no backend. Both English and Arabic are supported; use the
language toggle on the welcome or sign-in screen, or Account › Language.

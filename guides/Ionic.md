# Ionic

## Complete documentation

https://ionicframework.com/docs/vue/your-first-app

To begin, let's install the latest version of the Ionic CLI.

```bash
    npm install -g @ionic/cli@latest
```

Install Ionic Tooling

```bash
    npm install -g @ionic/cli@latest native-run cordova-res
```

Next, create an Ionic Vue app that uses the "Tabs" starter template and adds Capacitor for native functionality:

```bash
    ionic start mobile tabs --type vue --capacitor
```

or Sidemenu

```bash
    ionic start mobile sidemenu --type vue --capacitor
```

Change into directory

```bash
    cd mobile
```

Next we'll need to install the necessary Capacitor plugins to make the app's native functionality work:

```bash
    npm install @capacitor/camera @capacitor/storage @capacitor/filesystem
```

Some Capacitor plugins, including the Camera API, provide the web-based functionality and UI via the Ionic PWA Elements library.

```bash
    npm install @ionic/pwa-elements
```

Run the app

```bash
    ionic serve
```
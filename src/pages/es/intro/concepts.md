---
previousText: 'What is Ionic Framework'
previousUrl: '/docs/intro'
nextText: 'Build Your First App'
nextUrl: '/docs/intro/first-app'
---

# Conceptos principales

Para aquellos completamente nuevos en el desarrollo de aplicaciones Ionic puede ser útil obtener un buen conocimiento de los conceptos básicos y las herramientas que hay detrás del proyecto. Antes de profundizar en temas complejos cubriremos los conceptos básicos de que es Ionic Framework y como funciona.

## UI Components

Ionic Framework es una librería de componentes UI, la cual es un conjunto de elementos reutilizables que sirven como bloques de construcción para una aplicación. Los componentes de Ionic están construidos con los [estándares web](/docs/faq/glossary#web-standards) usando HTML, CSS y JavaScript. Aunque los componentes están pre-construidos, están diseñados desde el principio para ser altamente personalizables de manera que las apps puedan hacer de cada componente el suyo propio, permitiendo que cada app tenga su propia apariencia. More specifically, Ionic components can be easily themed to globally change appearance across an entire app. For more information about customizing the look, please see [Theming](/docs/theming/basics).

## Adaptive Styling

Adaptive Styling is a built-in feature of Ionic Framework which allows app developers to use the same code base for multiple platforms. Every Ionic component adapts its look to the platform on which the app is running on. For example, Apple devices, such as the iPhone and iPad, use Apple's own <a href="https://www.apple.com/ios" target="_blank">iOS design language</a>. Similarly, Android devices use Google's design language called <a href="https://material.io/guidelines/" target="_blank">Material Design</a>.

By making subtle design changes between the platforms, users are provided with a familiar app experience. An Ionic app downloaded from Apple's App Store will get the iOS theme, while an Ionic app downloaded from Android's Play Store will get the Material Design theme. For the apps that are viewed as a Progressive Web App (PWA) from a browser, Ionic will default to using the Material Design theme. Additionally, deciding which platform to use in certain scenarios is entirely configurable. More information about adaptive styling can be found in [Theming](/docs/theming/basics).

## Navigation

Traditional web apps use a linear history, meaning that the user navigates forward to a page and can hit the back button to navigate back. An example of this is clicking around Wikipedia where the user is going forward and backward on the browser's linear history stack.

In contrast, mobile apps often utilize parallel, "non-linear" navigation. For example, a tabbed interface can have separate navigation stacks for each tab, making sure the user never loses their place as they navigate and switch between tabs.

Ionic apps embrace this mobile navigation approach, supporting parallel navigation histories that can also be nested, all while maintaining the familiar browser-style navigation concepts web developers are familiar with.

For apps that are built with Angular and `@ionic/angular`, we recommend using the <a href="https://angular.io/guide/router" target="_blank">Angular Router</a> which comes out of the box for every new Ionic 4 Angular app.

## Native Access

An amazing feature of apps built with web technologies (such as Ionic apps!) is that it can run on virtually any platform: desktop computers, phones, tablets, cars, refrigerators, and more! The same code base for Ionic apps can work on many platforms because it is based on web standards and common APIs that are shared across these platforms.

One of the most common use cases for Ionic is to build an app which can be downloaded from both the <a href="https://www.apple.com/ios/app-store/" target="_blank">App Store</a> and <a href="https://play.google.com/" target="_blank">Play Store</a>. Both iOS and Android software development kits (SDKs) provide [Web Views](/docs/building/webview) which render any Ionic app, while still allowing for *full* Native SDK access.

Projects such as <a href="https://capacitor.ionicframework.com/" target="_blank">Capacitor</a> and <a href="https://cordova.apache.org/" target="_blank">Cordova</a> are commonly used to give Ionic apps this access to Native SDKs. This means developers can quickly build out an app using common web development tools, and still have access to native features such as the device's accelerometer, camera, GPS, and more.

## Theming

At the core, Ionic Framework is built using <a href="https://developer.mozilla.org/en-US/docs/Web/CSS" target="_blank">CSS</a> which allows us to take advantage of the flexibility that <a href="https://developer.mozilla.org/en-US/docs/Web/CSS/Using_CSS_variables" target="_blank">CSS properties (variables)</a> provide. This makes it incredibly easy to design an app that looks great while following the web standard. We provide a set of colors so developers can have some great defaults, but we encourage overriding them to create designs that match a brand, company or a desired color palette. Everything from the background color of an application to the text color is fully customizable. More information on app theming can be found in [Theming](/docs/theming/basics).
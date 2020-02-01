<img src="https://raw.githubusercontent.com/felangel/bloc/master/docs/assets/bloc_logo_full.png" height="60" alt="Bloc" />

[![build](https://github.com/felangel/bloc/workflows/build/badge.svg)](https://github.com/felangel/bloc/actions)
[![codecov](https://codecov.io/gh/felangel/Bloc/branch/master/graph/badge.svg)](https://codecov.io/gh/felangel/bloc)
[![Star on GitHub](https://img.shields.io/github/stars/felangel/bloc.svg?style=flat&logo=github&colorB=deeppink&label=stars)](https://github.com/felangel/bloc)
[![style: effective dart](https://img.shields.io/badge/style-effective_dart-40c4ff.svg)](https://github.com/tenhobi/effective_dart)
[![Flutter.io](https://img.shields.io/badge/flutter-website-deepskyblue.svg)](https://flutter.io/docs/development/data-and-backend/state-mgmt/options#bloc--rx)
[![Awesome Flutter](https://img.shields.io/badge/awesome-flutter-blue.svg?longCache=true)](https://github.com/Solido/awesome-flutter#standard)
[![Flutter Samples](https://img.shields.io/badge/flutter-samples-teal.svg?longCache=true)](http://fluttersamples.com)
[![Discord](https://img.shields.io/discord/649708778631200778.svg?logo=discord&color=blue)](https://discord.gg/Hc5KD3g)
[![License: MIT](https://img.shields.io/badge/license-MIT-purple.svg)](https://opensource.org/licenses/MIT)

---

Biblioteka do przewidywalnego zarządzania stanem ułatwiająca implementacje [wzorca projektowego BLoC](https://www.didierboelens.com/2018/08/reactive-programming---streams---bloc).

| Package                                                                            | Pub                                                                                                    |
| ---------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------ |
| [bloc](https://github.com/felangel/bloc/tree/master/packages/bloc)                 | [![pub package](https://img.shields.io/pub/v/bloc.svg)](https://pub.dev/packages/bloc)                 |
| [bloc_test](https://github.com/felangel/bloc/tree/master/packages/bloc_test)       | [![pub package](https://img.shields.io/pub/v/bloc_test.svg)](https://pub.dev/packages/bloc_test)       |
| [flutter_bloc](https://github.com/felangel/bloc/tree/master/packages/flutter_bloc) | [![pub package](https://img.shields.io/pub/v/flutter_bloc.svg)](https://pub.dev/packages/flutter_bloc) |
| [angular_bloc](https://github.com/felangel/bloc/tree/master/packages/angular_bloc) | [![pub package](https://img.shields.io/pub/v/angular_bloc.svg)](https://pub.dev/packages/angular_bloc) |

## Przegląd

<img src="https://raw.githubusercontent.com/felangel/bloc/master/docs/assets/bloc_architecture.png" alt="Bloc Architecture" />

Celem tej biblioteki jest ułatwienie separacji _prezentacji_ od _logiki biznesowej_, ułatwiając testowanie i ponowne użycie.

## Dokumentacja

- [Oficjalna Dokumentacja](https://bloclibrary.dev)
- [Pakiet Bloc](https://github.com/felangel/Bloc/tree/master/packages/bloc/README.md)
- [Pakiet Flutter Bloc](https://github.com/felangel/Bloc/tree/master/packages/flutter_bloc/README.md)
- [Pakiet Angular Bloc](https://github.com/felangel/Bloc/tree/master/packages/angular_bloc/README.md)

## Migracja

- [Uaktualnij wersję z v0.x na v2.x ](https://dev.to/mhadaily/upgrade-to-bloc-library-v1-0-0-for-flutter-and-angular-dart-2np0)

## Przykłady

<div style="text-align: center">
    <table>
        <tr>
            <td style="text-align: center">
                <a href="https://bloclibrary.dev/#/fluttercountertutorial">
                    <img src="https://bloclibrary.dev/assets/gifs/flutter_counter.gif" width="200"/>
                </a>
            </td>            
            <td style="text-align: center">
                <a href="https://bloclibrary.dev/#/flutterinfinitelisttutorial">
                    <img src="https://bloclibrary.dev/assets/gifs/flutter_infinite_list.gif" width="200"/>
                </a>
            </td>
            <td style="text-align: center">
                <a href="https://bloclibrary.dev/#/flutterfirebaselogintutorial">
                    <img src="https://bloclibrary.dev/assets/gifs/flutter_firebase_login.gif" width="200" />
                </a>
            </td>
        </tr>
        <tr>
            <td style="text-align: center">
                <a href="https://bloclibrary.dev/#/flutterangulargithubsearch">
                    <img src="https://bloclibrary.dev/assets/gifs/flutter_github_search.gif" width="200"/>
                </a>
            </td>
            <td style="text-align: center">
                <a href="https://bloclibrary.dev/#/flutterweathertutorial">
                    <img src="https://bloclibrary.dev/assets/gifs/flutter_weather.gif" width="200"/>
                </a>
            </td>
            <td style="text-align: center">
                <a href="https://bloclibrary.dev/#/fluttertodostutorial">
                    <img src="https://bloclibrary.dev/assets/gifs/flutter_todos.gif" width="200"/>
                </a>
            </td>
        </tr>
    </table>
</div>

### Dart

- [Counter](https://github.com/felangel/Bloc/tree/master/packages/bloc/example) - przykład jak stworzyć `CounterBloc` (czysty dart).

### Flutter

- [Counter](https://bloclibrary.dev/#/fluttercountertutorial) - przykład jak stworzyć `CounterBloc` aby zaimplementować klasyczną aplikację Flutter Counter.
- [Form Validation](https://github.com/felangel/bloc/tree/master/examples/flutter_form_validation) - przykład jak użyć pakietów `bloc` oraz `flutter_bloc` aby zaimlementować walidację formularza.
- [Bloc with Stream](https://github.com/felangel/bloc/tree/master/examples/flutter_bloc_with_stream) - przykład jak połączyć `bloc` do `Stream` oraz aktualizować interfejs użytkownika w odpowiedzi na dane z `Stream`.
- [Infinite List](https://bloclibrary.dev/#/flutterinfinitelisttutorial) - przykład jak użyć pakietów `bloc` oraz `flutter_bloc` aby zaimplementować nieskończenie przewijalną listę.
- [Login Flow](https://bloclibrary.dev/#/flutterlogintutorial) - przykład jak użyć pakietów `bloc` oraz `flutter_bloc` aby zaimplementować Przepływ Logowania.
- [Firebase Login](https://bloclibrary.dev/#/flutterfirebaselogintutorial) - przykład jak użyć pakietów `bloc` oraz `flutter_bloc`  aby zaimplementować logowanie poprzez Firebase.
- [Github Search](https://bloclibrary.dev/#/flutterangulargithubsearch) - przykład jak stworzyć aplikację Github Search  używając pakietów `bloc` oraz `flutter_bloc`.
- [Weather](https://bloclibrary.dev/#/flutterweathertutorial) - przykład jak stworzyć aplikację Weather używając pakietów `bloc` oraz `flutter_bloc`. Aplikacja wykorzystuje `RefreshIndicator` aby zaimplementować "pociągnij-by-odświeżyć" jak również dynamiczne motywy.
- [Todos](https://bloclibrary.dev/#/fluttertodostutorial) - przykład jak stworzyć aplikację Todos używając pakietów `bloc` oraz `flutter_bloc`.
- [Timer](https://github.com/felangel/bloc/tree/master/examples/flutter_timer) - przykład jak stworzyć Timer używając pakietów `bloc` oraz `flutter_bloc`.
- [Firestore Todos](https://bloclibrary.dev/#/flutterfirestoretodostutorial) - przykład jak stworzyć aplikację Todos używając pakietów `bloc` oraz `flutter_bloc`  która integruje się z Cloud Firestore.
- [Shopping Cart](https://github.com/felangel/bloc/tree/master/examples/flutter_shopping_cart) - przykład jak stworzyć aplikację Shopping Cart używając pakietów `bloc` oraz `flutter_bloc` na podstawie [flutter samples](https://github.com/flutter/samples/tree/master/provider_shopper).
- [Dynamic Form](https://github.com/felangel/bloc/tree/master/examples/flutter_dynamic_form) - przykład jak użyć pakietów `bloc` oraz `flutter_bloc` aby zaimplementować dynamiczny formularz który pobiera dane z repozytorium.

### Web

- [Counter](https://github.com/felangel/Bloc/tree/master/examples/angular_counter) - przykład jak stworzyć aplikację `CounterBloc` w AngularDart.
- [Github Search](https://github.com/felangel/Bloc/tree/master/examples/github_search/angular_github_search) - przykład jak stworzyć aplikację Github Search używając pakietów `bloc` oraz `angular_bloc`.

### Flutter + Web

- [Github Search](https://github.com/felangel/Bloc/tree/master/examples/github_search) - przykład jak stworzyć aplikację Github Search i współdzielić kod pomiędzy Flutter'em oraz AngularDart'em.

## Artykuły

- [bloc package](https://medium.com/flutter-community/flutter-bloc-package-295b53e95c5c) - Wprowadzenie do pakietu bloc  z wysoko poziomową architekturą i przykładami.
- [login tutorial with flutter_bloc](https://medium.com/flutter-community/flutter-login-tutorial-with-flutter-bloc-ea606ef701ad) - Jak stworzyć pełny przepływ logowania używając pakietów bloc oraz flutter_bloc.
- [unit testing with bloc](https://medium.com/@felangelov/unit-testing-with-bloc-b94de9655d86) - Jak przeprowadzać testy jednostkowe bloc stworzonych w poradniku logowania we Flutterze.
- [infinite list tutorial with flutter_bloc](https://medium.com/flutter-community/flutter-infinite-list-tutorial-with-flutter-bloc-2fc7a272ec67) - Jak stworzyć nieskończoną listę używając pakietów bloc oraz flutter_bloc.
- [code sharing with bloc](https://medium.com/flutter-community/code-sharing-with-bloc-b867302c18ef) - Jak współdzielić kod pomiędzy aplikacją mobilną napisaną we Flutterze a aplikacją sieciową napisaną w AngularDart.
- [weather app tutorial with flutter_bloc](https://medium.com/flutter-community/weather-app-with-flutter-bloc-e24a7253340d) - Jak zbudować aplikację o pogodzie która wspiera dynamiczne motywy, pociągnij-by-odświeżyć oraz interakcje przy pomocy REST API używając pakietów bloc oraz flutter_bloc.
- [todos app tutorial with flutter_bloc](https://medium.com/flutter-community/flutter-todos-tutorial-with-flutter-bloc-d9dd833f9df3) - Jak zbudować aplikację 'Do Zrobienia' używając pakietów bloc oraz flutter_bloc.
- [firebase login tutorial with flutter_bloc](https://medium.com/flutter-community/firebase-login-with-flutter-bloc-47455e6047b0) - Jak zbudować w pełni funkcjonalny przepływ logowania/rejestracji używając pakietów bloc oraz flutter_bloc wraz z Firebase Authentication i Google Sign In.
- [flutter timer tutorial with flutter_bloc](https://medium.com/flutter-community/flutter-timer-with-flutter-bloc-a464e8332ceb) - Jak stworzyć aplikację czasomierza używając pakietów bloc oraz flutter_bloc.
- [firestore todos tutorial with flutter_bloc](https://medium.com/flutter-community/firestore-todos-with-flutter-bloc-7b2d5fadcc80) - Jak stworzyć aplikację 'Do Zrobienia' używając pakietów bloc oraz flutter_bloc która integruje się z Cloud Firestore.

## Rozszerzenia

- [IntelliJ](https://plugins.jetbrains.com/plugin/12129-bloc-code-generator) - rozszerza IntelliJ/Android Studio o obsługę biblioteki Bloc i zapewnienie narzędzia dla efektywnego tworzenia Bloc dla aplikacji Flutter i AngularDart.
- [VSCode](https://marketplace.visualstudio.com/items?itemName=FelixAngelov.bloc#overview) - rozszerza VSCode o obsługę biblioteki Bloc i zapewnia narzędzia dla efektywnego tworzenia Bloc dla aplikacji Flutter i AngularDart.

## Społeczność

Dowiedz się więcej pod poniższymi linkami, które zostały dodane przy współpracy społeczności.

### Pakiety

- [Hydrated Bloc](https://pub.dev/packages/hydrated_bloc) - Rozszerzenie biblioteki zarządzania stanami `bloc` które automatycznie utrzymuje i przywraca stan `bloc`, autorstwa [Felix Angelov](https://github.com/felangel).
- [Bloc.js](https://github.com/felangel/bloc.js) - Port biblioteki zarządzania stanami `bloc` z języka Dart do JavaScript, autorstwa [Felix Angelov](https://github.com/felangel).
- [Flutter Bloc Extensions](https://pub.dev/packages/flutter_bloc_extensions) - Kolekcja widżetów pomocniczych zbudowana na pakiecie `flutter_bloc`, autorstwa [Ondřej Kunc](https://github.com/OndrejKunc).
- [Bloc Code Generator](https://pub.dev/packages/bloc_code_generator) - Generator kodu, który ułatwia pracę z blokiem, autorstwa [Adson Leal](https://github.com/adsonpleal).
- [Firebase Auth](https://pub.dev/packages/fb_auth) - Plugin do sieciowej oraz mobilnej autoryzacji w Firebase, autorstwa [Rody Davis](https://github.com/AppleEducate).
- [Form Bloc](https://pub.dev/packages/form_bloc) - Prosty sposób na tworzenie formularzy używając wzorca BLoC bez wielokrotnego powielania kodu, autorstwa [Giancarlo](https://github.com/GiancarloCode).

### Poradniki Wideo

- [Flutter Bloc Library Tutorial](https://www.youtube.com/watch?v=hTExlt1nJZI) - Wprowadzenie do biblioteki Bloc, autorstwa [Reso Coder](https://resocoder.com).
- [Flutter Youtube Search](https://www.youtube.com/watch?v=BJY8nuYUM7M) - Jak zbudować aplikację Youtube Search która ingeruje z API używając pakietów bloc oraz flutter_bloc, autorstwa [Reso Coder](https://resocoder.com).
- [Flutter Bloc - AUTOMATIC LOOKUP - v0.20 (and Up), Updated Tutorial](https://www.youtube.com/watch?v=_vOpPuVfmiU) - Zaktualizowany poradnik o pakiecie Flutter Bloc, autorstwa [Reso Coder](https://resocoder.com).
- [Dynamic Theming with flutter_bloc](https://www.youtube.com/watch?v=YYbhkg-W8Mg) - Poradnik jak używać pakietu flutter_bloc do implementacji dynamicznego motywu, autorstwa [Reso Coder](https://resocoder.com).
- [Persist Bloc State in Flutter](https://www.youtube.com/watch?v=vSOpZd_FFEY) - Poradnik jak używać pakietu hydrated_bloc do automatycznego utrzymywania stanu aplikacji, autorstwa [Reso Coder](https://resocoder.com).
- [State Management Foundation](https://www.youtube.com/watch?v=S2KmxzgsTwk&t=731s) - Wprowadzenie do zarządzania stanem przy użyciu pakietu flutter_bloc, autorstwa [Techie Blossom](https://techieblossom.com).
- [Flutter Football Player Search](https://www.youtube.com/watch?v=S2KmxzgsTwk) - Jak zbudować aplikację Football Player Search, która współdziała z interfejsem API używając pakietów bloc oraz flutter_bloc, autorstwa [Techie Blossom](https://techieblossom.com).
- [Learning the Flutter Bloc Package](https://www.youtube.com/watch?v=eAiCPl3yk9A&t=1s) - Nauka pakietu flutter_bloc na żywo, autorstwa [Robert Brunhage](https://www.youtube.com/channel/UCSLIg5O0JiYO1i2nD4RclaQ)
- [Bloc Test Tutorial](https://www.youtube.com/watch?v=S6jFBiiP0Mc) - Poradnik jak wykonywać testy jednostkowe używając pakietu bloc_test, autorstwa [Reso Coder](https://resocoder.com).

### Rozszerzenia

- [Feature Scaffolding for VSCode](https://marketplace.visualstudio.com/items?itemName=KiritchoukC.flutter-clean-architecture) - Rozszerzenie dla VSCode zainspirowane poradnikami o czystej architekturze [Reso Coder's](https://resocoder.com), które ułatwia szybko dodawać funkcje, autorstwa [Kiritchouk Clément](https://github.com/KiritchoukC).

## Opiekun

- [Felix Angelov](https://github.com/felangel)

# flutter-starting-guide
![header](header.png)

This is a collection of ressources, that helped me to learn appdevelopment with Flutter and Dart.

------------------
## 0. Vorbereitung
+ [ ] 0.1 [FVM installation](https://fvm.app/docs/getting_started/installation/)
+ [ ] 0.2 XCodes installieren

## 1. Grundlagen
Für den Start ist es hilfreich sich ersteinmal mit den Grundlagen der Programmiersprache Dart vertraut zu machen und anschließend ein grobes Gefühl für den Workflow bei der App Entwicklung zu bekommen.
+ [ ] 1.1 Einführung in die Programmiersprache Dart: [Dart Tour (en)](https://dart.dev/guides/language/language-tour)
+ [ ] 1.2 Was macht Flutter besonders [Flutter in 10 Minuten (de)](https://www.youtube.com/watch?v=SvfDnKDDfhk)
+ [ ] 1.3 (Wichtig) Dart Konzepte & Hintergründe [Dart Playlist (en)](youtube.com/watch?v=TF-TBsgIErY&list=PLjxrf2q8roU0Net_g1NT5_vOO3s_FR02J)
+ [ ] 1.4 Workflow verstehen [Anfänger Tutorial (de)](https://www.youtube.com/watch?v=wFwAkfAv3Us)
+ [ ] 1.5 Kennenlernen der Widgets [Widget of the Week (en)](https://youtu.be/R84AGg0lKs8)


## 2. Frameworks und Hilfsmittel
### 2.1 freezed (*Automatische Codegenerierung*)
Freezed ist ein Werkzeug, welches simplen aber umfangreichen Code automatisch generieren kann. Es ist sinnvoll sich zunächst mit freezed vertraut zu machen, da die Nutzung einger der nachfolgenden Pakete mit freezed erleichtert wird.
+ [ ] [Freezed Doku (en)](https://pub.dev/packages/freezed)

### 2.2 bloclib (*State Management*)
Bloclib ist ein Framework um Zustände (wie z.B. dargestellte Inhalte) losgelöst von der eigentlichen Dartstellung zu implementieren.
+ Installation, Nutzen und Konzepte 
+ [ ] [Installation (en)](https://bloclibrary.dev/#/gettingstarted)
+ [ ] Um den Nutzen zu verstehen, die Sektion [**Why Bloc**](https://bloclibrary.dev/#/whybloc) durchlesen
+ [ ] Die Sektion [**Architecture**](https://bloclibrary.dev/#/architecture) gibt bereits einen Einblick in welche Schichten professionelle Anwendungen aufgetrennt werden. (Mehr dazu kommt im Kurs *Flutter TDD Clean Architecture* )
+ [ ] [# Why Bloc + Freezed is a match made in heaven](https://dev.to/ptrbrynt/why-bloc-freezed-is-a-match-made-in-heaven-29ai)
+ [ ] [Example Freezed with Bloc](https://github.com/yh-luo/freezed_weather/blob/main/lib/weather/bloc/weather_bloc.dart)


+ Übungen
	Es empfielt sich die folgenden Flutter Tutorials in gegebener Reihenfolge nacheinander durchzuführen. Diese fangen sehr leicht an und nehmen immer weitere Konzepte mit auf. (Bitte nicht alle auf einmal!)
	+ [ ] [Counter App (en)](https://bloclibrary.dev/#/fluttercountertutorial)
	+ [ ] [Timer Tutorial (en)](https://bloclibrary.dev/#/fluttertimertutorial) 
	+ [ ] [Infinite List (en)](https://bloclibrary.dev/#/flutterinfinitelisttutorial)
	+ [ ] [Login (en)](https://bloclibrary.dev/#/flutterlogintutorial)
	+ [ ] [Weather (en)](https://bloclibrary.dev/#/flutterweathertutorial)
	+ [ ] [Todo App (en)](https://bloclibrary.dev/#/fluttertodostutorial)
	+ [ ] [Firebase Login (en)](https://bloclibrary.dev/#/flutterfirebaselogintutorial)

### 2.3 fpdart (*Functional Programming*)
Um dem Anwender eine bestmögliches Nutzererlebnis zu gewährleisten, versuchen wir Exceptions während der Laufzeit zu vermeiden. Ursache von Exceptions sind meist Situationen, in denen eine Funktion oder Methode Daten  abweichend von der gewünschten Form zurück gibt. Beispielsweise weil aufgrund mangelnder Internetverbindung gerade keine Daten aus dem Web abgerufen werden können. fpdart ermöglicht es ein Ergebnis zurück zu geben, welches entweder die gewonnen Daten kapselt oder auch keine und optional den Grund / Fehler dazu und somit die Notwendigkeit einer Exception elliminiert. 
+ [ ] [# How to use TaskEither in fpdart](https://www.sandromaglione.com/techblog/how-to-use-task-either-fpdart-functional-programming)

### 2.4 Isar Database
Um ein einheitliches System um Daten lokal auf dem Endgerät zu persistieren, bietet sich die Isar Datenbak an.
+ [ ] [Beginner Tutorials & Concepts (en)](https://isar.dev/tutorials/quickstart.html)
+ [ ] [Isar Database: How to use it with Flutter | Todo App(en)](https://medium.com/geekculture/isar-database-how-to-use-it-with-flutter-todo-app-978a2d7c85dd)

### 2.5 Riverpod 
Riverpod ist ein Tool um States (Andwendungszustände) einheitlich bei Bedarf bereitzustellen.
Dabei können bereits bestehdende Bloc Klassen verwendet werden.
Da die Dokumentation etwas knapp bemessen ist, lohnt es sich den Quellcode der Beispielanwendungen anzusehen.
+ [ ] [Riverpod: Getting Started (en)](https://riverpod.dev/docs/getting_started)

### 2.6 AutoRoute
Mit AutoRoute kann die Navigation einer Flutter Anwendung einfacher realisiert werden.
Daneben ist es möglich Parameter zu übergeben.
+ [ ] [AutoRoute Guide](https://pub.dev/packages/auto_route)

### 2.7 innFactory Boilerplate
Dieses Template sollte als Grundlage für die Flutter-Entwicklung genutzt werden. Die Architektur wird unter der Sektion *3. Flutter Architecture* erklärt. 
+ [ ] [Flutter Bricks (GitHub)](https://github.com/innFactory/flutter_bricks)

## 3. Flutter Architecture
[Flutter TDD Clean Architecture | Skript (en)](https://resocoder.com/2019/08/27/flutter-tdd-clean-architecture-course-1-explanation-project-structure/)
[Flutter TDD Clean Architecture | Videokurs (en)](https://www.youtube.com/playlist?list=PLB6lc7nQ1n4iYGE_khpXRdJkJEp9WOech)


## 4. Versionskontrolle mit GIT
+ [ ] [GitGame: learn git branching](https://learngitbranching.js.org/)
+ Naming Guidelines
	+ [ ] [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/#summary)
	+ [ ] [Semantic Versioning](https://semver.org/)

## Weiterführendes
+ [Flutter State Management Course (en)](https://www.youtube.com/watch?v=uXmOKTPsxOk&list=PL6yRaaP0WPkUf-ff1OX99DVSL1cynLHxO&index=1)

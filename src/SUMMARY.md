# রাষ্ট প্রোগ্রামিং ভাষা (Rust Programming)

[রাষ্ট প্রোগ্রামিং ভাষা (Rust Programming)](title-page.md)
[ভুমিকা](foreword.md)
[পরিচিতি পর্ব](ch00-00-introduction.md)

## শুরু হচ্ছে

- [প্রথম পদক্ষেপ](ch01-00-getting-started.md)

  - [কিভাবে Install করবেন](ch01-01-installation.md)
  - [হ্যালো ওয়ার্ল্ড (Hello World)](ch01-02-hello-world.md)
  - [হ্যালো, কার্গো!(Hello, Cargo!)](ch01-03-hello-cargo.md)

- [অনুমান খেলার ( Guessing Game Program)](ch02-00-guessing-game-tutorial.md)

- [সাধারণ প্রোগ্রামিং ধারণা](ch03-00-common-programming-concepts.md)

  - [চলক এবং পরিবর্তনশীলতা (Variables and Mutability)](ch03-01-variables-and-mutability.md)
  - [তথ্যের ধরণ (Data Type)](ch03-02-data-types.md)
  - [ফাংশন(Functions)](ch03-03-how-functions-work.md)
  - [মন্তব্য(Comments)](ch03-04-comments.md)
  - [নিয়ন্ত্রণ প্রবাহ-(Control Flow)](ch03-05-control-flow.md)

- [মালিকানা কি জিনিস - (Understanding Ownership)](ch04-00-understanding-ownership.md)

  - [মালিকানা কি? (Ownership)?](ch04-01-what-is-ownership.md)
  - [রেফারেন্স এবং গ্রহন(References and Borrowing)](ch04-02-references-and-borrowing.md)
  - [স্লাইস টাইপ (slice)](ch04-03-slices.md)

- [সম্পর্কিত ডেটা গঠনের জন্য কাঠামো ব্যবহার করা-(Using Structs to Structure Related Data)](ch05-00-structs.md)

  - [Structs ডিফাইন করা](ch05-01-defining-structs.md)
  - [Beispielprogramm mit Strukturen (structs)](ch05-02-example-structs.md)
  - [Methodensyntax](ch05-03-method-syntax.md)

- [Aufzählungen (enums) und Musterabgleich (pattern matching)](ch06-00-enums.md)
  - [Eine Aufzählung (enum) definieren](ch06-01-defining-an-enum.md)
  - [Das Kontrollflusskonstrukt `match`](ch06-02-match.md)
  - [Prägnanter Kontrollfluss mit `if let`](ch06-03-if-let.md)

## Grundlegende Sprachelemente

- [Wachsende Projekte verwalten mit Paketen (packages), Kisten (crates) und Modulen](ch07-00-managing-growing-projects-with-packages-crates-and-modules.md)

  - [Pakete (packages) und Kisten (crates)](ch07-01-packages-and-crates.md)
  - [Mit Modulen den Kontrollumfang und Datenschutz steuern](ch07-02-defining-modules-to-control-scope-and-privacy.md)
  - [Mit Pfaden auf ein Element im Modulbaum verweisen](ch07-03-paths-for-referring-to-an-item-in-the-module-tree.md)
  - [Pfade in den Gültigkeitsbereich bringen mit dem Schlüsselwort `use`](ch07-04-bringing-paths-into-scope-with-the-use-keyword.md)
  - [Module in verschiedene Dateien aufteilen](ch07-05-separating-modules-into-different-files.md)

- [Allgemeine Kollektionen](ch08-00-common-collections.md)

  - [Wertlisten in Vektoren ablegen](ch08-01-vectors.md)
  - [UTF-8-kodierten Text in Zeichenketten (strings) ablegen](ch08-02-strings.md)
  - [Schlüssel mit zugehörigen Werten in Hashtabellen ablegen](ch08-03-hash-maps.md)

- [Fehlerbehandlung](ch09-00-error-handling.md)

  - [Nicht behebbare Fehler mit `panic!`](ch09-01-unrecoverable-errors-with-panic.md)
  - [Behebbare Fehler mit `Result`](ch09-02-recoverable-errors-with-result.md)
  - [Wann `panic!` aufrufen und wann nicht?](ch09-03-to-panic-or-not-to-panic.md)

- [Generische Typen, Merkmale (traits) und Lebensdauer](ch10-00-generics.md)

  - [Generische Datentypen](ch10-01-syntax.md)
  - [Merkmale (traits): Gemeinsames Verhalten definieren](ch10-02-traits.md)
  - [Referenzen validieren mit Lebensdauern](ch10-03-lifetime-syntax.md)

- [Automatisierte Tests schreiben](ch11-00-testing.md)

  - [Tests schreiben](ch11-01-writing-tests.md)
  - [Steuern wie Tests ausgeführt werden](ch11-02-running-tests.md)
  - [Testverwaltung](ch11-03-test-organization.md)

- [Ein E/A-Projekt: Ein Kommandozeilenprogramm erstellen](ch12-00-an-io-project.md)
  - [Kommandozeilenargumente entgegennehmen](ch12-01-accepting-command-line-arguments.md)
  - [Eine Datei einlesen](ch12-02-reading-a-file.md)
  - [Refaktorierung um die Modularität und Fehlerbehandlung zu verbessern](ch12-03-improving-error-handling-and-modularity.md)
  - [Bibliotheksfunktionalität mit testgetriebener Entwicklung erstellen](ch12-04-testing-the-librarys-functionality.md)
  - [Mit Umgebungsvariablen arbeiten](ch12-05-working-with-environment-variables.md)
  - [Fehlermeldungen in die Standardfehlerausgabe anstatt der Standardausgabe schreiben](ch12-06-writing-to-stderr-instead-of-stdout.md)

## Denken in Rust

- [Funktionale Sprachelemente: Iteratoren und Funktionsabschlüsse (closures)](ch13-00-functional-features.md)

  - [Funktionsabschlüsse (closures): Anonyme Funktionen, die ihre Umgebung erfassen können](ch13-01-closures.md)
  - [Eine Reihe von Elementen verarbeiten mit Iteratoren](ch13-02-iterators.md)
  - [Unser E/A-Projekt verbessern](ch13-03-improving-our-io-project.md)
  - [Performanzvergleich: Schleifen vs. Iteratoren](ch13-04-performance.md)

- [Mehr über Cargo und Crates.io](ch14-00-more-about-cargo.md)

  - [Bauvorgang anpassen mit Freigabeprofilen (release profiles)](ch14-01-release-profiles.md)
  - [Kisten (crate) auf crates.io veröffentlichen](ch14-02-publishing-to-crates-io.md)
  - [Cargo-Arbeitsbereiche](ch14-03-cargo-workspaces.md)
  - [Installieren von Binärdateien mit `cargo install`](ch14-04-installing-binaries.md)
  - [Cargo um benutzerdefinierte Befehle erweitern](ch14-05-extending-cargo.md)

- [Intelligente Zeiger](ch15-00-smart-pointers.md)

  - [Mit `Box<T>` auf Daten im Haldenspeicher zeigen](ch15-01-box.md)
  - [Intelligente Zeiger wie normale Referenzen behandeln mit dem Merkmal (trait) `Deref`](ch15-02-deref.md)
  - [Programmcode beim Aufräumen ausführen mit dem Merkmal (trait) `Drop`](ch15-03-drop.md)
  - [Der referenzzählende intelligente Zeiger `Rc<T>`](ch15-04-rc.md)
  - [`RefCell<T>` und das innere Veränderlichkeitsmuster](ch15-05-interior-mutability.md)
  - [Referenzzyklen können zu einem Speicherleck führen](ch15-06-reference-cycles.md)

- [Furchtlose Nebenläufigkeit](ch16-00-concurrency.md)

  - [Mit Strängen (threads) Programmcode gleichzeitig ausführen](ch16-01-threads.md)
  - [Nachrichtenaustausch zwischen Strängen (threads)](ch16-02-message-passing.md)
  - [Nebenläufigkeit mit gemeinsamem Zustand](ch16-03-shared-state.md)
  - [Erweiterbare Nebenläufigkeit mit den Merkmalen (traits) `Sync` und `Send`](ch16-04-extensible-concurrency-sync-and-send.md)

- [Objektorientierte Sprachelemente von Rust](ch17-00-oop.md)
  - [Charakteristiken objektorientierter Sprachen](ch17-01-what-is-oo.md)
  - [Merkmalsobjekte (trait objects) die Werte unterschiedlicher Typen erlauben](ch17-02-trait-objects.md)
  - [Ein objektorientiertes Entwurfsmuster implementieren](ch17-03-oo-design-patterns.md)

## Fortgeschrittene Themen

- [Muster (patterns) und Abgleich (matching)](ch18-00-patterns.md)

  - [Alle Stellen an denen Muster (patterns) verwendet werden können](ch18-01-all-the-places-for-patterns.md)
  - [Abweisbarkeit: Falls ein Muster (pattern) mal nicht passt](ch18-02-refutability.md)
  - [Mustersyntax](ch18-03-pattern-syntax.md)

- [Fortgeschrittene Sprachelemente](ch19-00-advanced-features.md)

  - [Unsicheres (unsafe) Rust](ch19-01-unsafe-rust.md)
  - [Fortgeschrittene Merkmale (traits)](ch19-03-advanced-traits.md)
  - [Fortgeschrittene Typen](ch19-04-advanced-types.md)
  - [Erweiterte Funktionen und Funktionsabschlüsse (closures)](ch19-05-advanced-functions-and-closures.md)
  - [Makros](ch19-06-macros.md)

- [Abschlussprojekt: Einen mehrsträngigen (multi-threaded) Webserver erstellen](ch20-00-final-project-a-web-server.md)

  - [Einen einsträngigen (single-threaded) Webserver erstellen](ch20-01-single-threaded.md)
  - [Unseren einsträngigen (single-threaded) Webserver in einen mehrsträngigen (multi-threaded) Webserver verwandeln](ch20-02-multithreaded.md)
  - [Kontrolliertes Beenden und Aufräumen](ch20-03-graceful-shutdown-and-cleanup.md)

- [Anhang](appendix-00.md)
  - [A - Schlüsselwörter](appendix-01-keywords.md)
  - [B - Operatoren und Symbole](appendix-02-operators.md)
  - [C - Ableitbare Merkmale (traits)](appendix-03-derivable-traits.md)
  - [D - Nützliche Entwicklungswerkzeuge](appendix-04-useful-development-tools.md)
  - [E - Ausgaben](appendix-05-editions.md)
  - [F - Übersetzungen des Buchs](appendix-06-translation.md)
  - [G - Wie Rust erstellt wird und „nächtliches Rust“](appendix-07-nightly-rust.md)

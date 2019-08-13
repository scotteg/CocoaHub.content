![](https://github.com/pedrommcarrasco/Cocoahub.content/blob/master/banner.jpg?raw=true)

Events, news and articles related to Apple's programming ecosystem in the palm of your hand. For more details about CocoaHub visit https://cocoahub.app.

Everyone can contribute to CocoaHub by adding content and keeping it updated! In order to do so there are just *some* guidelines that you need to follow!

# Guidelines

## Commit messages / Pull Requests Titles

The syntax should be **Action** | **Area** | **Title**.

* Actions: **Added**, **Updated** and **Deleted**.
* Area: **New**, **Edition**, **Article**, **Event**, **Recommendation** and **Contributor**
* Title: For example in case of a new, it's the title of the new. 

## JSON Structures

### New

```json
{
    "title": "Swift by Sundell Podcast 54: Swift 5.1, iOS 13 and iPadOS",
    "description": "Join John Sundell and his special guests, Benedikt Terhechte & Bas Broek, and hear them talking about iOS 13, iPadOS, Swift 5.1 and much more!",
    "url": "https://www.swiftbysundell.com/podcast/54",
    "curator": {
        "name": "Pedro Carrasco",
        "url": "https://twitter.com/pedrommcarrasco"
    },
    "tags": [
        "podcast"
    ]
}
```

There are 6 possible tags for news, being:

* **apple**
* **evolution**
* **press**
* **podcast**
* **newsletter**
* **community**

### Edition

```json
{
    "title": "Edition #1",
    "description": "A first edition packed with articles regarding our new toys from WWDC 2019.",
    "date": "2019-06-14T17:00:00+0000"
}

```

### Article

```json
{
    "title": "Unit Testing Asynchronous Code",
    "edition": 9,
    "tags": ["testing"],
    "url": "https://www.vadimbulavin.com/unit-testing-async-code-in-swift/",
    "author": {
        "name": "Vadim Bulavin",
        "url": "https://twitter.com/V8tr"
    },
    "curator": {
        "name": "Pedro Carrasco",
        "url": "https://twitter.com/pedrommcarrasco"
    }
}
```

There are 16 possible tags for articles, being:

* **architecture**
* **server**
* **business**
* **career**
* **debugging**
* **design**
* **gaming**
* **language**
* **storage**
* **testing**
* **tipsAndTricks**
* **tooling**
* **ui**
* **web**
* **workflow**
* **other**

### Event

```json
{
    "name": "Swift Aveiro",
    "url": "https://www.swiftaveiro.xyz",
    "logo": "https://firebasestorage.googleapis.com/v0/b/pedrommcarrasco-cocoahub.appspot.com/o/events%2Fswiftaveiro.jpg?alt=media&token=77ee75b3-a4fe-433c-baab-ba6e4d356b46",
    "startDate": "2019-06-20T12:00:00+0000",
    "endDate": "2019-06-21T12:00:00+0000",
    "country": "Portugal",
    "city": "Aveiro",
    "tags": [
      "tickets"
    ]
}
```

There are 2 possible tags for events, being:

- **tickets**, while there are tickets available to buy
- **callForPapers**, while there's an active Call for Papers

### Contributor

```jso
{
    "name": "Ana Filipa Ferreira",
    "url": "https://github.com/anafpf"
}
```

### Recommendation

```json
{
    "logo": "https://firebasestorage.googleapis.com/v0/b/pedrommcarrasco-cocoahub.appspot.com/o/recommendations%2Funwrap.jpg?alt=media&token=1847e83e-98a8-48e4-af53-86d467875af2",
    "name": "Unwrap",
    "description": "by Paul Hudson",
    "url": "https://apps.apple.com/app/unwrap/id1440611372"
}
```

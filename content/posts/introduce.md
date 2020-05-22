---
title: "Introduce"
date: 2020-05-22T15:16:31+09:00
draft: false
tags: ["preview", "Syntax Highlighting", "tag-5"]
categories: ["Syntax Highlighting"]
toc: false
type: "post"
---

# Welcome to my blog

```dart
import 'package:flutter/material.dart';

void main() => runApp(MyApp());

class MyApp extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      title: 'Welcome to Flutter',
      home: Scaffold(
        appBar: AppBar(
          title: Text('Welcome to Flutter'),
        ),
        body: Center(
          child: Text('Hello World'),
        ),
      ),
    );
  }
}
```
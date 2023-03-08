# Selamat-pagi-dunia
import 'package:flutter/material.dart';

void main() {
  runApp(
    MaterialApp(
      title: 'Selamat Pagi Dunia',
      home: Scaffold(
        appBar: AppBar(
          title: Text('Selamat Pagi Dunia'),
        ),
        body: Center(
          child: Text(
            'Sudahkah kamu bersyukur hari ini?',
            textDirection: TextDirection.ltr,
          ),
        ),
        floatingActionButton: FloatingActionButton(
          tooltip: 'Random',
          child: Icon(Icons.restart_alt),
          onPressed: null,
        ),
      )
    )
  );
}

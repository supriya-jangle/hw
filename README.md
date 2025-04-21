import 'package:flutter/material.dart';
void main() => runApp(MyApp());
class MyApp extends StatelessWidget {
 @override
 Widget build(BuildContext context) {
 return MaterialApp(
 home: SizeContainerDemo(),
 );
 }
}
class SizeContainerDemo extends StatelessWidget {
 @override
 Widget build(BuildContext context) {
 return Scaffold(
 appBar: AppBar(title: Text('Container Size')),
 body: Center(
 child: Container(
 height: 100,
 width: 200,
 color: Colors.orange,
 child: Center(
 child: Text('Sized Container'),
 ),
 ),
 ),
 );
 }
}

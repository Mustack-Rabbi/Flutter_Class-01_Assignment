## Class 1:

> Topics: Android Studio , VS Code, Create New Apps, About Flutter etc..

## flutter_class_01_assignment

আপনাদের একটি এ্যাপ ক্রিয়েট করতে হবে এবং সেটি রান করতে হবে (Android Studio বা VS Code যেকোনো একটিতেই প্রজেক্ট ক্রিয়েট করে রান করলেই হবে)। প্রজেক্ট ক্রিয়েট করার পর যেই কোডটি লিখা আছে, কমেন্টের মাধ্যমে প্রত্যেকটি লাইন বর্ননা করতে হবে। এছাড়াও এ্যপটির কালার, এ্যপবারের লিখা, লজিক এগুলো পরিবর্তন করতে হবে।

## Flutter_Class-01_Assignment

## Getting Started

A new Flutter project.

Then...

1.

```dart
     theme: ThemeData(
        // blue colour poriborton kore, amar priyo color green korlam
        primarySwatch: Colors.green,
      ),
```

2.

```dart
 // Ekhane home page title chenge korlam
      home: const MyHomePage(title: 'Class-01 Assignment')
```

3.

```dart
 // Ekhane _counter valu 10 kore dilam
 int _counter = 10;

  void _incrementCounter() {
    setState(() {
      _counter--;
    });
  }
```

4.

```dart

  void _incrementCounter() {
    setState(() {
      // counter er por ++ kete -- korlam
      _counter--;
    });
  }
```

5.

```dart
  children: <Widget>[
            const Text(
              'বাটন চাপা চাপি করলে মান ১ করে কম (-) হবে:',
            ),
            Text(
              '$_counter',
              style: Theme.of(context).textTheme.headline4,
            ),
          ]
```

6.

```dart
 tooltip: 'Decrement',
```

## Result

### Image : 1/3

![Class-01_Assignment_01](https://user-images.githubusercontent.com/86506002/184536682-fbeaa68c-2da6-426a-810d-b9d3ab0a490c.jpg)


### Image : 2/3

![Class-01_Assignment_02](https://user-images.githubusercontent.com/86506002/184536712-09d924dd-c23b-432a-8154-3e9ea874cd22.jpg)


### Image : 3/3


![Class-01_Assignment_03](https://user-images.githubusercontent.com/86506002/184536722-1eb1b2a2-0411-414d-a1e2-29abca3b6463.jpg)

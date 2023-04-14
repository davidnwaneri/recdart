# dart_rec

# Recursion in Dart Language

This repository contains examples and explanations of recursion in Dart language.

## What is recursion?

Recursion is a technique of solving a problem by breaking it down into smaller sub-problems that are similar in nature to the original problem. In programming, recursion involves a function calling itself repeatedly until a base condition is met.

## Why use recursion?

Recursion can simplify complex problems that can be broken down into smaller, similar sub-problems. It can also make code more readable and easier to maintain.

## Getting Started

To use these examples, you will need to have Dart installed on your machine. You can download and install Dart from the official website [https://dart.dev/get-dart](https://dart.dev/get-dart), or you can quickly get started by using [dartpad](https://dartpad.dev/).

Once you have Dart installed, you can clone this repository using the following command:

```
git clone https://github.com/davidnwaneri/dart_rec.git
```

## Examples

This repository contains the following examples of recursion in Dart language:

1. **[Palindrome](#palindrome):** A palindrome is a word, phrase, number, or sequence of characters that reads the same backward as forward. For example, "racecar".

### Palindrome

```dart
bool isPalindrome(String input) {
  if (input.length <= 1) return true;

  final firstChar = input.split('')[0];
  final secondChar = input.split('')[input.length - 1];

  if (firstChar == secondChar) {
    return isPalindrome(input.substring(1, input.length - 1));
  }
  return false;
}
```


## Contributing

If you would like to contribute to this repository, please fork the repository and create a pull request with your changes. We welcome contributions of all kinds, including bug fixes, new examples, and improvements to existing examples.

## License

This repository is licensed under the MIT License. See the LICENSE file for more information.



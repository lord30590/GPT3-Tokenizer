# GPT3 Tokenizer
GPT3 encoder & decoder tool written in Swift

## About
## Install with Swift Package Manager

Add this repository url to Swift Package Manager

```
https://github.com/aespinilla/GPT3-Tokenizer.git
```

## Usage

```swift
import GPT3_Tokenizer

let gpt3Tokenizer = GPT3Tokenizer()

let text = "hello 👋 world 🌍"

// Encode
let encoded = gpt3Tokenizer.encoder.enconde(text: text)
print(encoded)

// Decode
let decoded = gpt3Tokenizer.decoder.decode(encode: encoded)
print(decoded)

```

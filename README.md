# Parity Property — Ruby Gem Practice 🔹

A sample Ruby gem for checking parity‑related properties of numbers.
This project was created to learn how to build, structure, test, and publish a Ruby gem from scratch.

---

## 📌 Summary

`parity_property` is a lightweight Ruby gem that provides utility methods to determine whether a number is:

* even
* odd
* and other parity‑related checks

It was created as a learning exercise to understand Ruby gem conventions, packaging, and distribution.

---

## 🧠 Key Topics

* Ruby gem development
* Project structure and conventions
* Packaging and distribution
* Unit testing with RSpec
* Versioning best practices

---

## 📦 Features (Example)

* `even?` – Check if a number is even
* `odd?` – Check if a number is odd
* Utility methods that can be easily extended

---

## 🧠 Example Usage

### 1. Install locally (for development)

```bash id="gemrun1"
git clone https://github.com/KavitaJadhav/parity_property.git
cd parity_property
bundle install
```

### 2. Build the gem

```bash id="gemrun2"
gem build parity_property.gemspec
```

### 3. Use in a Ruby project

```ruby id="gemrun3"
require 'parity_property'

puts ParityProperty.even?(4)  # => true
puts ParityProperty.odd?(7)   # => true
```

---

## 📂 Project Structure

```text id="gemstr1"
lib/
 ├── parity_property.rb          # main module
 └── parity_property/ 
       helpers.rb                # helper methods
parity_property.gemspec         # gem configuration
README.md
```

📌 The gem follows standard Ruby gem conventions to ensure easy packaging and future distribution.

---

## 🎯 Purpose

* Learn the anatomy of a Ruby gem
* Explore packaging and usage workflows
* Understand testing, versioning, and documentation for reusable libraries

---

## 🧪 Testing

Tests are written with RSpec:

```bash id="gemtest1"
bundle exec rspec
```

Ensure all tests pass before building or releasing the gem.

---

## 🚀 Future Improvements

* Add more utility methods (e.g., parity statistics)
* Publish to RubyGems.org
* Add usage examples and GitHub Action for CI tests

---

## 💡 Key Insight

Building a gem is a great way to:

* modularize functionality
* share reusable code
* understand the Ruby ecosystem

Even simple utilities help reinforce fundamentals.

---

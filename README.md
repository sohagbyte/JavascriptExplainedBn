# Javascript Programming Language শিখুন সম্পূর্ণ বাংলায়!!
এইটা একটা রিপোজিটরি যেইখানে আমি মূলত জাভাস্ক্রিপ্ট প্রোগ্রামিং সম্পর্কিত বিষয়াদি নিয়ে লেখালেখি করার চেষ্টা করি। <br>
## Table of Contents
**1. [Introduction to JavaScript Variable](#introduction-to-js-variable)**
**2. [var, let and const Explained](#var-let-and-const-explained)**

















<a name = "introduction-to-js-variable"> </a>
## What is Variable in JavaScript?
প্রোগ্রামিং এ **Variable** জিনিসটাকে আমরা একটা **Container** হিসাবে চিন্তা করতে পারি, যেইটাতে আমরা আমাদের **Data/Information** গুলো **Store** করতে পারি। এবং যখন দরকার হবে তখন তখন আমরা আমাদের সেই **Store** করা **Data** গুলোকে একটা প্রোগ্রামের বিভিন্ন জায়গায় ব্যাবহার করতে পারি, বা সেইগুলোকে নিয়ে কাজ  করতে পারি।
আমরা যখন কোনো **Variable Declare** করি তখন সেইটা **Store** হয় আমাদের কম্পিউটারে থাকা **Memory** তে । অর্থ্যাৎ, আমরা মেমোরির কিছু **Space Reserve** করছি একেকটা **Variable Declare** করার জন্য।
## Why Variable?
জাভাস্ক্রিপ্টে একটা প্রোগ্রামে অনেকগুলো কারণেই আমরা Variable ব্যাবহার করে থাকি। তার ভিতরে উল্লেখযোগ্য কিছু কারণ হচ্ছে -</br>
1. **Data Storage:** </br>
  একটা প্রোগ্রামে Variable ব্যাবহার করার অন্যতম প্রধাণ কারণ হচ্ছে Data গুলোকে Store করে রাখা। এমনকি অনেকটা **Structured Way** তে Store করে রাখা, যাতে প্রয়োজন অনুযায়ী আমরা সেইগুলোকে Access করতে পারি।</br>
2. **Dynamic Content:** </br>
  Variable  এর ব্যাবহার আমাদের প্রোগ্রামকে আরো বেশি **Dynamic** করে ফেলতে সাহায্য করে। যেমন কাজের প্রয়োজনে আমাদের অনেক **Data Change/Modify** করা লাগতে পারে। এই জিনিসটা আমরা Variable ব্যাবহার করার মাধ্যমে করে ফেলতে 
  পারি।
3. **Increase Readability:** </br>
  আমাদের প্রোগ্রামে যখন সঠিক Variable এর নামকরণ করতে পারি যেইটা দ্বারা আমাদের Declare করা Variable টা ঠিক কি কাজ করছে সেইটা বোঝা যায়, তখন সেই প্রোগ্রাম এর **Readability** অনেক বেড়ে যায়। পরে যখন অন্য কোনো 
  ডেভেলপার আমাদের লেখা কোডগুলোকে **Maintain** করবে তখন তারা খুব সহজেই সেইগুলাকে Maintain করতে পারবে। কারণ তারা Already জানবে ঠিক কোন কাজে আমরা কোন Variable টা Declare করেছি।

এইগুলা ছাড়াও আরো অনেক কারণে,  যেমন একটা প্রোগ্রাম এর **Reusablity Increase** করা, **Mathematical/Logical Operations** করা, **Scope Management** সহ আরো অনেক কাজেই আমরা Variable ব্যাবহার করতে পারি। </br>
## Variable Naming Rules in JavaScript: </br>
1. জাভাস্ক্রিপ্ট হচ্ছে একটা **Case Sensitive** Programming Language. যেইটার অর্থ হচ্ছে **Capital Letter** এ লেখা **“A”** আর **Small Letter** এ লেখা **“a”** দুইটা পুরোপুরি আলাদা জিনিস। এই জিনিসটা মাথায় রেখেই আমাদের Variable এর নামকরণ করা উচিৎ।
2. Variable এর নামকরণের জন্য আমরা জাভাস্ক্রিপ্টে থাকা **Reserved Keywords** গুলো ব্যাবহার করতে পারব না।
3. Variable এর নাম অবশ্যই কোনো **Letter, Dollar sign($), বা Underscore(_)** দিয়ে শুরু করতে হবে।
4. কোনো Variable এর নাম কোনো **Number** দিয়ে শুরু হইতে পারবে না, কিন্তু নামের শেষে আমরা চাইলে **Number** ব্যাবহার করতে পারি।
5. প্রতিটা Variable এর নাম **Unique** বা একটার চাইতে অন্যটা আলাদা হওয়া দরকার, যাতে একটা থেকে অন্যটাকে সহজেই আলাদা করা যায়। এই ইউনিক নামগুলাকে জাভাস্ক্রিপ্টে **Identifier** ও বলে।  এতে করে **Naming Conflict** হয় না।
6. Variable এর নাম হিসাবে আমরা **Short Name (যেমনঃ x, y)** ও ব্যাবহার করতে পারি, আবার **Descriptive Name (যেমনঃ myName, Number1)** ও ব্যাবহার করতে পারি।

আমরা যখন **Descriptive Name** ব্যাবহার করে Variable Declare করি তখন চাইলে আমরা অনেকগুলো **Method Follow** করে সেইটা করতে পারি। যেমনঃ </br>

### Camel Case: </br>
এই পদ্ধতিতে _দুই বা ততোধিক_ **Word** কে একসাথে লেখার জন্য প্রথম **Word** এর প্রথম **Letter** টা **Small Letter** এ হবে এবং তার পরের সবগুলো **Word** শুরুর **Letter** টা **Capital Letter** এ হবে। এই **Camel Case** ই সবচাইতে বেশি ব্যাবহার করা হয়।
**Example:**
```javascript
let myName = “Sohag”;
```
### Snake Case: </br>
এই পদ্ধতিতে ***দুই বা ততোধিক*** **Word** কে একসাথে লেখার জন্য বা প্রতিটা নতুন **Word** কে যুক্ত করার জন্য **Underscore(_)** ব্যাবহার করা হয়। </br>
**Example:**
```javascript
let my_name = “Sohag”;
```
### Pascal Case: </br>
এই পদ্ধতিতে ***দুই বা ততোধিক*** **Word** কে একসাথে লেখার জন্য প্রতিটা **Word** এর প্রথম **Letter** সবসময় **Capital Letter** হবে।</br>
**Example:**
```javascript
let MyName = “Sohag”;
```
উপরের প্রতিটা পদ্ধতিই সঠিক, একেকজন একেকটা Prefer করে, এই আরকি! আপনি আপনার পছন্দমত একটা **Method Follow** করে **Variable Declare** করতে পারেন। </br>
>**Note:** আপনি শুধু যে **Variable Declare** করার জন্য উপরোক্ত Method গুলো Follow করবেন, এমনটা কিন্তু না। **Array, Function** সহ যেকোনো কিছু Declare করার জন্য এই একই নিয়মই প্রযোজ্য হবে। </br>

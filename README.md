# Javascript Programming Language শিখুন সম্পূর্ণ বাংলায়!!
এইটা একটা রিপোজিটরি যেইখানে আমি মূলত জাভাস্ক্রিপ্ট প্রোগ্রামিং সম্পর্কিত বিষয়াদি নিয়ে লেখালেখি করার চেষ্টা করি। <br>
## Table of Contents
**1. [Introduction to JavaScript Variable](#introduction-to-js-variable)** </br>
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
  Variable  এর ব্যাবহার আমাদের প্রোগ্রামকে আরো বেশি **Dynamic** করে ফেলতে সাহায্য করে। যেমন কাজের প্রয়োজনে আমাদের অনেক **Data Change/Modify** করা লাগতে পারে। এই জিনিসটা আমরা Variable ব্যাবহার করার মাধ্যমে করে ফেলতে পারি।

4. **Increase Readability:** </br>
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

<a name="var-let-and-const-explained"></a>
## var, let and const Explained: </br>
জাভাস্ক্রিপ্ট এ আমরা মূলত ৪ ভাবে **Variable Declare** করতে পারি। এইগুলা হচ্ছে </br>
1. ***var*** ব্যাবহার করে,
2. ***let*** ব্যাবহার করে,
3. ***const*** ব্যাবহার করে,
4. ***automatically (Implicitly Created and Assigned Values Without Explicit Declaration) / ICAVWED / Undeclared*** </br>

### var: </br>
এই ```var``` keyword জাভাস্ক্রিপ্ট এ প্রথম Introduce করানো হয় ১৯৯৫ সালে এবং ২০১৫ সাল পর্যন্ত জাভাস্ক্রিপ্ট এর **ES6** Version আসার আগে পর্যন্ত ```var``` ব্যাবহার করেই জাভাস্ক্রিপ্ট এ Variable Declare করা হতো। যদিও এখন var ব্যাবহার করে Variable Declare করতে নিরুৎসাহিত করা হয়। কিন্তু যদি আমাদের অনেক পুরাতন ***Code Base*** নিয়ে কাজ করতে হয়, যেখানে তারা var ব্যাবহার করেছে, সেই সমস্ত প্রজেক্টে আমাদের var ব্যাবহার করেই Variable Declare করা লাগতে পারে। </br>

**Declare Variable Using var:** </br>
Javascript এ var ব্যাবহার করে Variable Declare করার জন্য আমাদের প্রথমে ***var*** শব্দটা বা keyword টা লিখতে হবে, তারপরে Variable এর ***Name*** লিখতে হবে, এবং সবশেষে ***Semi-colon*** দিয়ে Statement টা Close করতে হবে। যেমনঃ ```var  myGf;``` । এই var keyword টা কিন্তু সবসময় **Small Letter** এ ই লিখতে হবে। তা না হইলে Javascript আমাদের Error দেখাবে। </br>

উপরে এখন পর্যন্ত আমরা শুধু Variable Declare করেছি, কিন্তু এতে কোনো **Value Assign** করি নাই। </br>

**Assign Value Using var:** </br>
কোনো Variable এ ***Value Assign*** করার জন্য আমরা ***Equal Sign (=)*** ব্যাবহার করি, এই  **Equal Sign (=)** টাকে Javascript এ ***Assignment Operator*** ও বলা হয়। এই Javascript এ কোনো জিনিস Equal কি না এইটা বোঝা্র জন্য কিন্তু এই  **Operator** ব্যাবহার করা হয় না। এই **Equal Sign (=)** টা Javascript এ ব্যাবহার করা হয় ***Variable*** এ ***Value Assign*** করার জন্য। </br>
যেমন:
```javascript
var myGf;
myGf = 'Sadia';
```
 </br>
উপরের জিনিসটা আবার Explain করি, এইখানে = এই Operator টা দিয়ে কিন্তু এইটা বোঝানে হচ্ছে না, যে myGf আর Sadia এই ২ টা জিনিস সমান বা Equal. বরং এইটা বোঝানে হচ্ছে যে, myGf  Variable টার ভিতরে Sadia নামের Value টাকে Assign করে দাও। 

আমরা আগেই একটা Example দিসিলাম না যে, Variable জিনিসটা হচ্ছে একটা **Container** এর মত, যেইখানে আমরা আমাদের **Value** গুলো **Store** করে রাখি। এইখানেও কিন্তু same জিনিসটাই হচ্ছে, এইখানে আমরা ***myGf*** নামের Variable টার ভিতরে ***‘Sadia’*** নামের Value টাকে **Store** করে রাখছি। 

>**নোটঃ** আমরা চাইলে কিন্তু Variable Declare করার সময় ই **Value Assign** করে দিতে পারি। </br>

**Re-declare Variable Using var:** </br>
**Re-declare*** বলতে বোঝায় একই নামে ২ টা Variable Declare  করা। যেমনঃ </br>
```javascript
var carName = 'BMW';
var carName = 'AUDI';
console.log(carName); //AUDI
```
উপরে আমরা var ব্যাবহার করে একই নামে **```carName```** দুইটা Variable Declare করেছি। এক্ষেত্রে আমাদের Code এ কোনো Error আসবে না। 
কিন্তু এইখানে একটা Twist আছে, এই **```carName```** Variable টা যদি আমরা console.log করে output দেখতে চাই, তাহলে দেখব আমাদের **AUDI** দেখাচ্ছে ouput হিসাবে। কিন্তু আমরা তো প্রথম Value টা  দিয়েছিলাম **BMW** । তাহলে **BMW** কে বাদ দিয়ে **AUDI** কে কেন Output হিসাবে  দেখাচ্ছে।
এর কারণ হচ্ছে, আমরা পরে যেই Value টা **Assign** করব সেইটার **Priority** বেশি, এবং নিচের Variable টা উপরের Variable টা কে **Overwrite** করে ফেলছে।</br>

**Re-assign Value Using var:**
**Re-assign** বলতে বোঝায় **একই** Variable এ 2 টা **Value Assign** করা। যেমনঃ
```javascript
var carName = 'BMW';
    carName = 'AUDI';
    
console.log(carName); //AUDI
```
উপরে আমরা **```carName```** নামের Variable টা তে প্রথমে **Value Assign** করেছি, **BMW** এবং পরে আমার সেই একই Variable এ **Value Assign** করেছি **AUDI**. 
আমরা কিন্তু এইখানে ২ টা Variable  Declare করি নাই, বরং Variable  একটাই, জাস্ট Value টা **Change** করেছি। 
এবং এইখানে নিচে যেই Value টা Assign করা থাকবে সেইটার **Priority** বেশি থাকবে এবং উপরেরটাকে নিচের Value টা **Overwrite** করে ফেলবে, যার কারণে Output হিসাবে নিচের Value টাই দেখাবে। </br>

## Why var?
এখনকার দিনে var ব্যাবহার করাটা মোটেও **Recommended** না, কিন্তু তবুও আপনার অনেক জায়গায় **var** ব্যাবহার  করা লাগতে পারে, যখন:

- আপনি পুরাতন ***Code Base*** নিয়ে কাজ করছে যেইখানে var ব্যাবহার করা হয়েছে। এইরকম জায়গায় আপনি ***Code Refactor*** করতে পারবেন না বেশিরভাগ সময়, তাই সেখানে অনেকটা বাধ্য হয়েই var ব্যাবহার করতে হবে।
- যখন আপনার ***Global-Scoped or Function-Scoped Variable*** দরকার হবে যেইটা আপনি সবজায়গায় **Access** করতে চান, তখন আপনার var ব্যাবহার করা লাগতে পারে।

## Why Not var?
var ব্যাবহার না করার অনেকগুলা কারণ আছে তার ভিতরে অন্যতম কারণ হচ্ছে ***Accidental Naming Conflicts.*** আমরা জানি, var হচ্ছে ***Global-Scoped or Function-Scoped*** এবং আমরা চাইলে এইটাকে **Re-assign**, বা **Re-declare** ও করতে পারি। অনেক সময় ভুল করে একই নামে **২** বার **Variable Declare** করে ফেলতে পারি যেইখানে একেকটা Variable হয়ত একেকটা কাজের জন্য Declare করে ছিলাম। পরে এইটা মনে না থাকলে দেখব, আমরা এক ধরনের রেজাল্ট expect করছি কিন্তু রেজাল্ট পাচ্ছি আরেক ধরনের।

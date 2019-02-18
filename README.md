# improve your coding skills

Made for Juniors
----
If you are a Senior Developer or having confidence with your code, You don't have to check it.

This is not a code-cop or linters
----
* It DOES NOT enforce you to keep strict coding style.
* It DOES NOT find vulnerabilities or compiler warnings.
* it DOES check consistency of conventions and namings, and addional basic validations irrespectively of your coding styles.

Alright, Let's take a look
----
```cs
using System;
using UnityEngine;
using System.Net;

class AmIGreat {
  public static void Main() {
    IntroducingMyself();
  }
  
  // Prints single line of message.
  
  public static void IntroducingMyself() {
    Console.WriteLine("Hi, My name is Xinu");
  }
}
```

Above code will generate 3 warnings:
```
* Unordered using derective: System.Net.
* Comments without following codeline. 
* Method name should be started with VERB: IntroducingMyself.
```

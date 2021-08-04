"Head First Object Oriented Analysis and Design is a refreshing look at subject of OOAD. What sets this book apart is its focus on learning. The authors have made the content of OOAD accessible and usable for the practitioner."
--Ivar Jacobson, Ivar Jacobson Consulting
_____________________________________
# Chapter 1
* **What's a great software?**
  * Make sure your software does what thecustomer wants it to do.
    * This step focuses on the customer Make sure the app does what it’s supposed to do FIRST. This is where getting good requirements and doing some analysis comes in.
  * Apply basic OO principles to add flexibility.
    * Once your software works, you can look for any duplicate code that might have slipped in, and make sure you’re using good OO programming techniques.
  * Strive for a maintainable, reusable design.
    * Got a good object-oriented app that does what it should? It’s time to apply patterns and principles to make sure your software is ready to use for years to come.

* **Don’t create problems to solve problems.**

* **Tips to find mismatched object type.**
  * Objects should do what their names indicate.
    * For example object Jet can land() or takeOff() but it can't takeTicket()
  * Each object should represent a single concept.
    * You don’t want objects serving double or triple duty.
  * Unused properties are a dead giveaway.

* **Encapsulation allows you to hide the inner workings of your application’s parts, but yet make it clear what each part does.**
  * The idea behind encapsulation is to protect information in one part of your application from the other parts of your application. In its simplest form, you can protect the data in your class from the rest of your app by making that data private. But sometimes the information might be an entire set of properties
  * That’s the power of encapsulation: by breaking up the different parts of your app, you can change one part without having to change all the other parts. In general, you should encapsulate the parts of your app that might vary away from the parts that will stay the same.
* **Delegation**
  * Delegation is when an object needs to perform a certain task, and instead of doing that task directly, it asks another object to handle the task (or sometimes just a part of the task).
* **Loosely coupled**
  * Loosely coupled is when the objects in your application each have a specific job to do, and they do only that job. So the functionality of your app is spread out over lots of well-defined objects, which each do a single task really well.
* **OOA&D is about writing great software, not doing a bunch of paperwork!**
  * Customers are satisfied when their apps **WORK**.
  * Customers are satisfied when their apps **KEEP WORKING**.
  * Customers are satisfied when their apps can be **UPGRADED**.
  * Programmers are satisfied when their apps can be **REUSED**.
  * Programmers are satisfied when their apps are **FLEXIBLE**.

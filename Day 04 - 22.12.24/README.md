# Important points to remember in ts:
* Class name starts with a capital letter
* If we do not define an access modifier - by default it is `public`



# Ts VS Java
* TS must use `this` keyword in the class function - in order to access class member
* TS can use `set` and `get` keywords
* TS constructor is defined with the built-in word: `constructor`
* TS has 2 ways to create down-casting: `<>` and `as`
* We can not overrload functions in js and in ts (but we can use optional parameters - with `?`)




<div dir="rtl">

# תרגיל:


צרו ממשק בשם IFly המכיל:

פונקציה fly  - מקבלת כפרמטר את המהירות. מחזירה void

פונקציה  land- לא מקבלת פרמטרים. מחזירה boolean (האם הנחיתה הצליחה)

צרו את המחלקות הבאות המממשות את IFly:
## מטוס
##### מאפיינים

* שם הטייס- מחרוזת
* שם חברת התעופה- מחרוזת
* יעד – מחרוזת

## עפיפון
##### מאפיינים
* צבע- מחרוזת
* מחיר- מספר (חיובי בלבד)

## ציפור
##### מאפיינים
* סוג הציפור - מחרוזת
* גיל – מספר (חיובי בלבד)
* צבע – מחרוזת


## בתכנית הראשית:
צור פונקציה בשם createIFly המחזירה אובייקט מסוג IFly – הפונקציה תגריל מספר רנדומלי בטווח 0-2:

אם המספר שהתקבל הוא 0 – תחזיר אובייקט מסוג ציפור

אם המספר שהתקבל הוא 1 – תחזיר אובייקט מסוג מטוס

אם המספר שהתקבל הוא 2 – תחזיר אובייקט מסוג עפיפון

### צור מערך מטיפוס IFly באורך 10 תאים

אתחל כל תא במערך באמצעות קריאה לפונקציה createIFly

עבור כל תא במערך- בצע קריאה לפונקציהfly  ולפונקציה  land

 

בהצלחה!!

</div>
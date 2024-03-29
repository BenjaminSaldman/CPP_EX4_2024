# מטלה 4 - קורסים (Inheritance)
במטלה הזאת נממש מהלך של קורס באוניברסיטה.
### קורס
כל קורס מורכב משם הקורס (Name), מספר המרצים, מספר המתרגלים וכמות הסטדונטים שלוקחים את הקורס. המטרה של התרגיל היא "לסמלץ" מהלך תקין של קורס.

### אדם
לכל אדם יש את השם שלו, שם המשפחה שלו ומספר תעודת זהות משלו.
עליכם לממש את הפעולה ``` print ``` כדי להדפיס את הפרטים של אותו האדם.

### תפקידים
לכל קורס יש כמה אנשים עם תפקידים מסוימים.
1. מרצה (Professor) - המרצה יכול ללמד, לפרסם מבחן (רק לאחר שכל המרצים לימדו את הקורס), לפרסם ציונים למבחן (רק לאחר שפרסם את המבחן), לענות על ערעורים ולסיים את הקורס (רק לאחר שכל הסטודנטים עברו את הקורס עם ציון של 60 ומעלה).
2. מתרגל (Teaching Assistant) - המתרגל יכול לפרסם מטלה (רק לאחר שכל המרצים לימדו את הקורס), לתת ציונים למטלה (רק אחרי שכל הסטודנטים הגישו את המטלה) ולפרסם את הציונים של הסטודנטים. נקודה חשובה - רק מתרגל אחד יכול לפרסם מטלה בכל פעם, כלומר אם יש 2 מתרגלים בקורס כלשהו והמתרגל הראשון פרסם מטלה, אז המתרגל השני יוכל לפרסם את המטלה הבאה ברגע שהמטלה הנוכחית מסתיימת (נותנים ציונים לסטודנטים).
3. סטודנט (Student) - יכול להכין שיעורי בית (בתנאי שפורסמה מטלה), לגשת למבחן (בתנאי שפורסם מבחן) ולערער על הציון של המטלה (בתנאי שקיבל ציון).



עליכם לכתוב את הקבצים הרלוונטיים כדי שהפקודות ``` make demo ``` ו-``` make test ``` יעבדו.

בהצלחה!

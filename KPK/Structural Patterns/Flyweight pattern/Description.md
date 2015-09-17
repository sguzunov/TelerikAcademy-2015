**Flyweight pattern**

Основната цел на Flyweight pattern-а е да се намали употребата на ресурси, когато е работи с голям брой идентични обекти.
Flyweight е обект, който успява да оптимизира употребата на памет, чрез споделяне на колкото се може повече подобни обекти.
Всеки обект, който използва споделен ресурс, получава единствено референция към него. Flyweight използва подобие на factory method,
за да генерира споделения обект. Factory-то проверява дали искания обект е създаден и решава дали да върне вече създадения такъв, или 
да се създаде нов.
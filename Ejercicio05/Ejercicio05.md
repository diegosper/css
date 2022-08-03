1. selección de todos los elementos  
    *{}
2. Selección de todos los elementosde tipo p  
    p{}
3. Selección del elemento con id title-1  
    #title-1{}
4. Selección de todos los elementos que pertenezcan a la clase .bg-yellow  
    .bg-yellow{}
5. Selección de todos los elementos que tengan el atributo id  
    [id]{}
6. Selección de todos los elementos que tengan el atributo id y como valor title-1  
    [id="title-1"]{}
7. Selección de todos los elementos que tengan el atributo href con un valor https://www.yahoo.com  
    [href="https://www.yahoo.com"]{}
8. Selección de todos los elementos que tengan el atributo class con un valor que empiece por title  
    [class^="title"]{}
9. Selección de todos los elementos que tengan el atributo href y acaben en .com  
    [href$=".com"]{}
10. Selección de todos los elementos que tengan el atributo class con un valor title, title-1, title-2,...  
    [class*="title"]{}  
    VERIFICAR
11. Selección de todos los elementos que tengan un atributo href y cuyo valor contenga 127  
    [href*="127"]{}
12. Selección de todos los elementos que tengan el atributo href y cuya valor empiece por http  
    [href^="http"]
13. Selección de los elementos que sean a, p o h1 desde una única regla CSS  
    a,p,h1{}
14. Selección de todos los elementos que pertenezcan a main y que sean p  
    main p{}
15. Selección del siguiente elemento que sea hermano de h1  
    h1 + *  {}
    VERIFICAR
16. Selección de todos los elementos hermanos de h1  
    h1 ~ * {}
17. Selección de todos los elementos hijos directos de main
    main > * {}

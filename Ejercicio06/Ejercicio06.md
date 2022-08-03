1. Intro:  
    li:first-child
2. Level 1:  
    p:not(.foo)
3. Level 2:  
    li:nth-of-type(2n+3)  
    devs choice: li:nth-child(2n + 3)
4. Level 3:  
    div > *
5. Level 4:  
    [data-item]  
6. Level 5:  
    span:nth-of-type(1n+3)  
    devs choice: p ~ span  
7. Level 6:  
    form>*:not(:disabled)
    devs choice: :enabled
8. Level 7:  
    [id="one"],[id="two"],[id="five"],[id="six"],[id="nine"]
    devs choice: #one, #two, #five, #six, #nine  
9. Level 8:   
    a + span  
10. Level 9:  
    #foo > .foo  
11. Level 10:  
    div>div>code:last-child:not(.foo)  
    devs choice: div div span + code:not(.foo)






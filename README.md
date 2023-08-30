At this link you can find this pagination demo : 

https://zerber011.github.io/pagination_demo/

Intresting part is in line 58 in CSS.  If select just '.current' class, it's not gonna work! 
Why!? Couse of line 46. Line 46 has priority 'Selector Specifitity ( 0,2,0 ) 
and 'current' class has ( 0,1,0 ) and stroke will be gray, not green as shuold be. 
It need to selecct both classes 'page-link and current' BUT without space between,
and just in that case hover and the stroke will be applied. 
I hope you can understand what I mean. 

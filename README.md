flex-tile - плитка(грид) без строк
===============================
### Пример, когда вам нужно будет её использовать:
Грид без конкретных строк, где каждый элемент занимает свою высоту и сразу за ним идёт следующий.


|―――|       gap |―――|       gap |―――|  
|..............| gap |..............| gap |..............|  
|..............| gap |..............| gap |―――|  
|..............| gap |..............| gap gap gap  
|―――|       gap |..............| gap |―――|  
gap  gap gap      |..............| gap |..............|    
|―――|       gap |..............| gap |..............|  
|..............| gap |―――|       gap |..............|  
|..............| gap    gap    gap gap      |―――|  
|..............| gap |―――|       gap gap gap  
|..............| gap |..............| gap |―――|  
|..............| gap |―――|       gap |..............|  
|―――|   gap  gap gap gap |..............|  
gap gap gap gap gap gap |―――|   

Но лучше вам глянуть example.html.  
Можно адаптировать, количество колонок высчитвает по максимальной ширине одного из элементов.

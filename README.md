# toetsmodel
Grading aid for Dutch exams where CITO publishes grading models with bolletjes

The `bolletjesmodel.html` file has a model on top:

```
var model = { 
   "toets": "Havo WisB 2022.2",
   "vragen": [
      { "naam": "Logaritme en parabool",
        "bolletjes": [ 3,2,5 ]
      },
      { "naam": "Gooilandkaart",
        "bolletjes": [ 6 ]
      },
      { "naam": "Wortel en cirkel",
        "bolletjes": [ 3,7 ]
      },
      { "naam": "Sinusoïden en somfunctie",
        "bolletjes": [ 4,7 ]
      }
      ]
  }
```
The suggested way of working is to make a branch for a new exam and edit the model to match it.

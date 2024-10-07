#Funciton Calling using Gemini from Google.<br>
![Gemini](Gemini.png)
---
### Advantages.
- The model can define the funcitons from its docs without needing to define it yourself, but write the docs with a specific style.
- The model doesn't run the function itselt, but it tells you the functions to be called and you run it yourself, or you can give the model this property.
- Gemini permit funciton calling using its best models but with limited tries per some time that is found it its pricing docs here: https://ai.google.dev/pricing 
but I think it is still efficient.
- The model can output more that one model to be called at the same time depending on the user input.
- There are many states to choose from to control the behaviour of the model when replying to the user input.
- If you want a specific style, you can detect it using enum, and pydantic libraries.
- There are another property, that if you have a story or an article, you can using the same method of function calling to extract the elements of the story or the article with a good precision.

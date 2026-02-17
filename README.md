# Code-Auditing
Code Auditing with GenAI

The Technical Reflection:
1. The "Bloat" Check:
   a. The AI did not use unnecessary div for the contact form from what I can tell. I think it is because of the simplicity of the form. I realize that AI tries to style everything that at some extend it becomes unnecessary. With that said, I did find some redudancies in styling. Such as applying different styles to the same thing such as the focus styles. I also found redudancy in padding from different elements that I think could cause overlapping spacing. Other than that, I didn't find other wrong use of elements. 

2. Specificity & Maintainability:
   a. AI didn't use overly specific selectors. Again, I think it is because of the simpliciy of my CSS. I think it would of added more specific selectors if it was a bigger project. The AI did add other specific selectors, but none are too hard to override. Most of them could be overridden with class or id selectors.
   b. The AI did create CSS Variables for colors and other elements. The variables were used consistently but hard-coded hex values were still used for some elements. For example, background used a hard-coded hex value,instead of a custom variable.
    
The Verdict:
    a. In my opinion, better styling was added but it is definitely more complex. The AI created CSS variables, but didn't used it consistently. Some things are overdone or unnecessary that could cause a crash. In some ways, the complexity is better such as the css variables, and the hover effects. In the mindset of a basic form, the AI version is more complex in postive and negative ways.
    b. I feel like there could be a couple that I would remove, but the main specific rule would be the styling for hover effects on the fieldset element. I would remove the rest of the redudant styling in hover effects. Also, the webkit element. Not sure exactly how that works, but I feel it could be adjusted without it. 




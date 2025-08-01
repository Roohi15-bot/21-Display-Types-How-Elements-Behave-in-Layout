The display property in CSS defines how an HTML element is rendered on the page — whether it stacks, flows inline, takes space, or not at all.

# 1. display: block

    div {
      display: block;
    }
    
 Behavior:
> Takes up full width

> Forces a line break after itself

> Can set width and height

Common block elements:

          <div>, <section>, <p>, <h1>–<h6>, <form>
      
Example:
> div I am block 1 /div

> div I am block 2 /div

 Appears one below the other, stacking vertically.

 #  2. display: inline
 
        span {
          display: inline;
       }
       
Behavior:

> Stays within the same line

> Does not respect width/height

> Only takes as much space as needed

Common inline elements:

          <span>, <a>, <strong>, <em>, <label>
          
Example:

           <span>Hello</span> <span>World</span>

 Appears side by side on the same line.

 # 3. display: inline-block
 
           .button {
               display: inline-block;
           }
           
Behavior:
> Behaves like inline (sits inline with others)

> Allows width and height to be set

> Great for buttons, badges, menu items

Example:

      <a class="btn">Click Me</a>
      
    .btn {
         display: inline-block;
         padding: 10px 20px;
         background: #1e90ff;
         color: white;
         border-radius: 5px;
         text-decoration: none;
      }
      
 Perfect for styled elements that still flow inline.

 # 4. display: none
 
    .hidden {
      display: none;
    }
    
Behavior:
> The element does not appear at all

> Not visible and not in document flow

> Different from visibility: hidden (which hides it but still takes space)

Use cases:
> Conditional UI rendering

> Dropdowns, modals, tabs

<p>This is visible</p>
<p class="hidden">You can't see me</p>

 


## Chapter 11: Color

ّ```color``` : The color property allows you to specify the color of text inside an element.
We can specify any color in CSS in one of three ways:

1. rgb values
2.hex codes
3. color names


``` /* color name */
h1 {
  color: DarkCyan;}
/* hex code */
h2 {
  color: #ee3e80;}
/* rgb value */
p {
  color: rgb(100,100,90);}
  /* color name */
h1 {
  color: DarkCyan;}
/* hex code */
h2 {
  color: #ee3e80;}
/* rgb value */
p {
  color: rgb(100,100,90);}
  ```

  ``` background-color ``` : the background-color property sets the color of the background

```
   body {
   background-color: rgb(200,200,200);}
h1 {
   background-color: DarkCyan;}
h2 {
   background-color: #ee3e80;}
p {
   background-color: white;}
   ```
## Understanding Color
Every color on a computer screen is created by mixing amounts of red, green, and blue. To find the color you want, we can use a ```color picker```.

![c](https://lh3.googleusercontent.com/proxy/DZSjh5YTBES75ow3gk68fVo8b1HHvzSePKcJbuNEwYLQCsP9n1n8w_0wwvcCgbpyX8eSn9aty-2DAMBaSS-UAVMt0qMF2hGW32In)


## Chapter 12: Text

### Typeface Terminology
   ```Serif   ```    ``` Sans-Serif   ```    ``` Monospace   ```


![](https://cdn.shopify.com/s/files/1/0860/0364/files/All-Standard_8ad42653-8981-4a2a-896e-fb6038e2b6b2.jpg?v=1500491871)

#### Weight : Light Medium Bold Black Style : Normal Italic Oblique Stretch : Condensed Regular Extended




# Underline & Strike

>text-decoration :

* none
* underline
* overline
* line-through
* blink


# Attribute Selectors
1. Existence : [] Matches a specific attribute

2. Equality : [=] Matches a specific attribute with a specific value

3. Space : [~=] Matches a specific attribute whose value appears in a spaceseparated list of words

4. Prefix : [^=] Matches a specific attribute whose value begins with a specific string

5. SubString : [*=] Matches a specific attribute whose value contains a specific substring

6. Suffix : [$=] Matches a specific attribute whose value ends with a specific string
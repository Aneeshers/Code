## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/Aneeshers/Codeine-/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.
# Java - Strings for competitive programming
### String
```
// Literal  
String s = "String";
// Using new as object
String s = new String("String");
```
#### Properties
##### Length
```
// Find the length of a string 
int length =  s.length();
```
##### Substring
```
//Substring - A part of a string
// Return a substring string starting from a certain index (Remeber index starts from 0)

"ThisIsAString".substring(9); // "String"
"ThisIsAString".substring(8,11); // AStr
```
##### Index of
```
"String are goofy".indexOf("are"); // 7
```
##### CharAt
``` 
First_Letter = string.charAt(1); // s
```

### Problem 1: Palindrome

```
public class palindrome 
{
	public static void main( String [] args)
	{
		// Create a scanner
        Scanner s = new Scanner(System.in)
       	String original, reverse;
        reverse = "";
        original = s.nextline();
        Length = original.lenght() - 1;
        // Create the reverse string
        for (int i = length; i>= 0; i--)
        {
        reverse = reverse + original.charAt(i);
        }
        // Check if reverse is equal to original
        if (original == reverse)
        {
        System.out.println("It is a palindrome");
        }
        else 
        {
        System.out.println("It is not a string");
        }
	}
}
```

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/Aneeshers/Codeine-/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.

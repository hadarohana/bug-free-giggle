# X-Team 66 Style Guide

<brief description of your team's opinion or philosophy regarding Style Guides>

## Naming conventions

We follow standard Java naming conventions that we were taught at UW Madison.

### Examples
* interfaces
  * Named like classes
  
  * `public interface InterfaceName(){}`
* classes
  * Upper camel case
  
 * `public class ClassName {}`
* exception types
  * Named like classes
  * Define as necessary
  
  * `class DuplicateKeyException extends RuntimeException`
* fields
  * Lower camel case
  * private with acessors and mutators if necessary
  
  * `private int count = 0`
* methods
  * Lower camel case
  
  * `private int myMethod() {}`
* parameters
  * Lower camel case
  * As descriptive as possible
  
  `public void myMethod(int num){}`
* local variables
  * Lower camel case
  * As descriptive as possible
  * No visibility modifiers
  
  * `int balanceFactor = 1`
* instance constants
  * All capitals with underscores
  * final
  
  * `final int NUM_COUNT = 5`
* class constants
  * All capitals with underscores
  * static and final
  
  * `static final double PI = 3.14`
## Commenting style for public and private members of a class or interface:

<brief statement of your team's commenting style>

### Examples

* classes
* fields
* constructors
* methods
* coding style (brackets, horizontal, and vertical spacing) for:
  * if statements
  * switch statement
  * while loops
  * for loops
  * enhanced for loops

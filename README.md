# Mad_Lib_Python
LEARN PHP
Mad Lib Functions
In this project, we’ll use PHP to write a function to fill in a Mad Libs story! Mad Libs are short stories with blank spaces, which get filled in by the user. The result is usually funny (or strange).

Mad Libs require:

A short story with blank spaces (asking for different types of words).
Words to fill in those blanks.
“Roses are Red” poem example:

Mad Libs Example

For this project, we provide the story, but it will be up to you to create a function that:

Takes desired words as arguments.
Returns the story with the words put into blanks in the right place.
Let’s begin!

Tasks
7/7 Complete
Mark the tasks as complete by checking them off
Create a Function
1.
Create a function generateStory with three input parameters:

$singular_noun
$verb
$color

Stuck? Get a hint
2.
Within the function, create a variable $story and assign it the last stanza of Robert Frost’s “Stopping by Woods on a Snowy Evening”:

The woods are lovely, dark, and deep.
But I have promises to keep,
And miles to go before I sleep,
And miles to go before I sleep.
Use newlines (\n) to ensure the lines break in the right location. Also use one at the beginning and the end to help with formatting.


Stuck? Get a hint
3.
For now, before adding in the “blanks”, let’s return the story from the function.


Stuck? Get a hint
4.
After the function definition, echo three separate invocations of generateStory with unique inputs. Use a singular noun, a verb, and a color, like the function parameters describe.


Stuck? Get a hint
5.
So far, the function isn’t super useful, since it is returning the same story every time.

Within the function, change the $story string so that it parses the $singularNoun variable where the word wood currently is, $verb where the word sleep appears (both locations), and $color where dark appears.


Stuck? Get a hint
6.
Great! Now, let’s add one more parameter to our function and allow the word miles to be replaced with a $distance_unit when the function is called (both places).

Remember to update the calls to generateStory to add this extra argument.


Stuck? Get a hint
7.
Now our story is a bit more fun! If you like, replace the story with your own.

You could also try using PHP’s built in string replace function str_replace to simplify your code.

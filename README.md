# Libft

My projects in ecol42 
This is my own recoded libc library with 10 custom functions and 10 bonus functions.
Each function in bonus part working with linked list:

ft_lstnew : Allocates (with malloc(3)) and returns a new
element. The variable ’content’ is initialized
with the value of the parameter ’content’. The
variable ’next’ is initialized to NULL.

ft_lstadd_front: Adds the element ’new’ at the beginning of the
list.

ft_lstsize: Counts the number of elements in a list.

ft_lstlast: Returns the last element of the list.

ft_lstadd_back: Adds the element ’new’ at the end of the list.

ft_lstdelone: Takes as a parameter an element and frees the
memory of the element’s content using the function
’del’ given as a parameter and free the element.
The memory of ’next’ must not be freed.

ft_lstclear: Deletes and frees the given element and every
successor of that element, using the function ’del’
and free(3).
Finally, the pointer to the list must be set to
NULL.

ft_lstiter: Iterates the list ’lst’ and applies the function
’f’ to the content of each element.

ft_lstmap: Iterates the list ’lst’ and applies the function
’f’ to the content of each element. Creates a new
list resulting of the successive applications of
the function ’f’. The ’del’ function is used to
delete the content of an element if needed.

Custom functions 

ft_putnbr_fd: Outputs the integer ’n’ to the given file
descriptor.

ft_putendl_fd: Outputs the string ’s’ to the given file
descriptor, followed by a newline.

ft_putstr_fd: Outputs the string ’s’ to the given file
descriptor.

ft_putchar_fd: Outputs the character ’c’ to the given file
descriptor.

ft_strmapi: Applies the function ’f’ to each character of the
string ’s’ to create a new string (with malloc(3))
resulting from successive applications of ’f’.

ft_itoa: Allocates (with malloc(3)) and returns a string
representing the integer received as an argument.
Negative numbers must be handled.

ft_split: Allocates (with malloc(3)) and returns an array
of strings obtained by splitting ’s’ using the
character ’c’ as a delimiter. The array must be
ended by a NULL pointer.

ft_strtrim: Allocates (with malloc(3)) and returns a copy of
’s1’ with the characters specified in ’set’ removed
from the beginning and the end of the string.

ft_strjoin: Allocates (with malloc(3)) and returns a new
string, which is the result of the concatenation
of ’s1’ and ’s2’.

ft_substr: Allocates (with malloc(3)) and returns a substring
from the string ’s’.
The substring begins at index ’start’ and is of
maximum size ’len’.


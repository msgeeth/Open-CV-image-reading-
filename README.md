Chane your file location in Line 2,3 and 4
I added r' to add the location becuase python undestand '\' as a scape charactor. In Python, the backslash \ is an escape character. 
It’s used to introduce special character sequences. For example, \n is a newline, and \t is a tab. When Python sees the \U in your string, it’s expecting a Unicode character code, but it’s not finding one, hence the error.

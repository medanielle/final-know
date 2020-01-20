## How do you prevent multiple dependencies from causing compilation errors?

KSAs: 254, 260, 264

## Answer
| A | B | ***C*** | D |
| :--- | :--- | :--- | :--- |
| Only #include source files | #include will overwrite the previous #include if they are the same file. | ***Use the preprocessor directives #ifndef, #define, and #endif to check if a header file was already included*** | Only one file can be #include into a file. |


Feedback:

- You should use include guards in your header files to stop the declarations from running if they were declared already.

[**<- Back To Basic Dev**](../../../Basic_Dev.md)


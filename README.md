# Problem

Given a file that contains a list of environment variables in the form, `Key=Value` create a python program that does the following:

1. Reads the file and maintains an in-memory representation of the environment variables.

    IN: "file3.env"

    `env_varaibles = my_python_program("file3.env")`

    OUT:

    `env_variables # contains the envars`

2. Prints the list of environment variables to standard out in the form `Key=Value` (without quotes).

    IN: "file3.env"

    `env_variables = my_python_program("file3.env")`

    OUT:

    ```
    # print operation on the env_variables
    Key=Value
    AnotherKey=Value
    ```

3. Allows the modification of a key's value.

4. Allows the deletion of a key.

5. Writes the in-memory representation of the variables back to the original file from which it was read.

6. Removes duplicate keys in the `.env` file (on read).

7. Skips lines with comments in the `.env` file (on read).

# mnesia-ext-frag-test
Test module Testing mnesia with external copies without really creating tables
Can be used by calling:

`test_mnesia_be:register()`

and then using:
`{test_mnesia_be, [Nodes]}`

in mnesia:create_table/2 to test creation of tables

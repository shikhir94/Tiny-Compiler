# Tiny-Compiler

Hey There,
To run the compiler as well as the language all you need to do:
1. download TWS.zip (of course!!)
2. unzip it to any of your directory.
3. open teminal(mac or linux) which is preferable not supported for windows.
4. go to your directory.
5. go to tws/.
6. run make
7. go to tws/tiny and run make 
8. run command chmod +x tc(you don't need to do it if tc is already executable)
9. that it!

some sample programs are there in tests folder as well as some complex test cases in test-progs folder

to run these test cases you need:
1. come to tiny directory.
2. type command ./tc tests/filename or test-progs/filename.
3. enjoy.

NOTE: 
1. before running any test case please open the test case first(in any editor you want) and read the comments describing what the test case do, will help you a lot.
2. some test cases might give a parse error as the compiler is configured like that.
3. its preferable to run test cases in test-progs/pr4.* as compiler is fully configured for that.
4. source code are in files CodeGenerator.c as well as Constrainer.c

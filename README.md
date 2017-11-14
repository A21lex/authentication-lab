# authentication-lab
Code for Authentication Lab for DTU Data Security course, Fall 2017. DTU Compute.

Written by Aleksandrs Levi, s162870

To test the program, launch the **ApplicationServer** class first, then **Client**.  

To test authentication, simply input different values of Password and Login as the parameters in service.authenticate call in line 57 of **Client** class before launching it:String token = service.authenticate(BobPw, BobLg). It should only work with provided examples at the top of the class, contained in variables BobPw and BobLg for ”Bob” and AlicePw and AliceLg for ”Alice”, as they are the only users present in the ”PublicUserFile”

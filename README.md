# language-name-to-be-determined
An in progress programming language that may one day be better than python itself.

# eventual syntax

1. a normal class

This is planned for what a normal class should look like:


    class SomeClass:
        # a class that does something.
        fn init(self):
            # initialization function for the class.
            self.something = "something to print here."

        fn printoutput(self):
            printout(self.something)

        fn printerror(self):
            # example function that prints self.something as an error.
            printerr(self.something)

    obj = SomeClass()
    obj.printout()
    obj.printerror()


2. async functions

Sometimes async functions are needed. Nowadays people depend on them for deplaying multiple functions (sometimes even one that is still executing) multiple times at the same exact moment in time. In normal syncronous mode this is almost impossible as code would either deadlock or wont fire on time. Meaning that without async support any chance to react in such events every time in a timely manber is needed.

Making an async function is planed to be strait forward as follows:

    async fn somefunction():
        # a function that does something.
        printout("this is a example async function.")


*Note: With async functions comes with the possibity for the use of an await token that will come when spmeone who knows how to implent it properly for functions and classes exampled later on in this file.*

3. if, else, try, except

got to admit, sometimes code can have exceptions when something fails. For that this means exceptions and intercepting for things like trying again for things like ratelimits to http requests where you can retry after some time. In many other cases people also need to compare values to know weather or not to throw an exception. In this case all of this part is required to have.

4. iterators and async iterators

lets face it, sometimes you have an object with certain sets of data you want to iterate through to get or compare the data in it. In such cases this is needed. And in other cases it is needed to iterate through things in like a json file or something.

5. Data compression

In many cases you might want to use it to do awesome things. Data compression is both good on the user and programmer, but bad on the people implemebting it to an language they are making.

6. More to add later on in time

Sometimes while writing things like this you think of something to add eventually. Such things could be things like an import system to use user code, an standard library, and other things like maybe some sort of ways to communicate and get data from the internet. Long story short things should be easy to the end user or programmer to use and call safely and in a timely manner.

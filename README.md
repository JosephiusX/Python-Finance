# Python-Finance

# Sec 1

4. Installation and Jupyter Setup

Jupyter notebooks are a dev environment. The code in this course can be used in any code editor. Jupyter just happens to be popular especially for data science and visualization. It includes:

        - environment manager
        - download manager
        - graphical interface to access a varieity of development environments.

google search ' anaconda download ' to find the latest link

        - download the latest version of the Individual Edition of Anaconda under Products.

        - open the exe.  file

        - install and check both boxes in advanced options even though one is not recomended.

        - after installed we can skip the tutorial and getting started

there are now 2 ways we can run anaconda

        - search computer for 'anaconda navigator':
            a graphical interface for the various development environments that anaconda comes with

launch jupyter notebooks which should open in the browser. this will shows our jupyter file system.

        ?? not sure if I did something wrong because desktop is not visible in my jupyter notebook.

        ** I can solve this by downloading the course materials zip files into downloads which is available in my jupyter notebooks file directory

To start a new notebook:

    home > New > Python3

now we can:

        - write python: 1 + 1
        - 'shift + enter' to output 2
        - 'alt + enter' to add a new line under the current one
        - to make the cell a markdown for notes:
            Cell > Cell type > markdown

# Sec 2: Python Crash Course

# Sec 3: NumPy

The basics:

        Data types:
            Numbers
            Strings
            Printing
            Lists
            Dictionaries
            Booleans
            Tuples
            Sets
        Comparison Operators
            if,elif, else Statements
            for Loops
            while Loops
            range()
            list comprehension
            functions
            lambda expressions
            map and filter
            methods

11. Introduction to NumPy Section

If we setup the invironment as instructed before NumPy is automatically included. One of the benifits of jupyter Notebook environment.

otherwise it can be installed with Pip or something like that

12. NumPy Arrays

Why use Numpy array? Why not just a list? There are lot's of reasons to use a Numpy array instead of a "standard" python list object. Our main reasons are:

        - Memory Efficiency of Numpy Array vs list
        - Easily expands to N-dimensional objects
        - Speed of calculations of numpy array
        - Broadcasting operations and functions with numpy
        - All the data science and machine learning libraries we use are built with Numpy

A list is Pythons array. For example:

        - create a list called my_list and call it after:
            my_list = [1,2,3]
            my_list

        - to see the output:
            shift + enter
                output:
                    [1, 2, 3]

        - turn 'my_list' into a NumPy array:
            np.array(my_list)

        - output:
            shift + enter
                result:
                    array([1, 2, 3])

currently this adds extra brackets but otherwise looks the same as before. To really see the difference I need to turn an list with many arrays into a NumPy array:

        - make variable and call it:
            my_matrix = [[1,2,3],[4,5,6],[7,8,9]]
            my_matrix

        - turn it into a NumPy array:
            np.array(my_matrix)
                result:
                    array([[1, 2, 3],
                           [4, 5, 6],
                           [7, 8, 9]])

NumPy has taken the data that was displayed horizontally and has it organized in a grid.

doing rest of notes in Jupyter

stopped at Linespace at 6:52

# 404B Lesson 2 Class Exercise - Function

## Instructions

### Split VS Code Window

You can drag `main.py` tab to the right side of the window to split the window into two panes. This will allow you to see the instructions and the code at the same time.

### Answering

You can answer the questions by writing your answers in the `main.py` file.

You can run the code by clicking the `Run` button on the top right corner of the editor.

The output will be shown in the `Terminal` tab at the bottom of the editor.

## Function Examples

- Sample 1, no parameter:

  ```python
  def function1():
      print('Running function one')
  
  function1()
  ----------------------
  > Running function one
  ```

- Sample 2, with parameter(s):

    ```python
    def echo(msg):
        print(f'I received: {msg}')

    echo('hello there')
    ----------------------
    > I received: hello there
    ```
  
- Sample 3, named parameter:

    ```python
  def echoes(msg1, msg2):
      print(f'I received {msg1} and {msg2}')
  
  echoes(msg2='there', msg1='hello')
  ----------------------
  > I received hello and there
  ```
  
## Questions

1. Modify the program to have following outputs:

    ```python
   def greet():
       print(f'Hi, human!')
 
    greet('Alice')
    greet('Bob')
    ----------------------
    Outputs:
    
    Hi, Alice!
    Hi, Bob!
    ```

2. Modify the program of Q4 to have following outputs:
  
    ```python
   def greet():
       print(f'Hi, ...')
 
 
    greet(name2='Bob', name1='Alex')

    ----------------------
    Outputs:
    
    Hi, Alex and Bob!
    ```

3. Add a function to validate the program below:
  
    ```python
    # TODO: Write your function here
 
    find_rect_area(width=12.3, height=45.6)
    ```

4. Write a program that produces as output the words of “Bought Me a Cat”.\
   Use functions for each verse and for repeated text.\
   Here is a part of the song's lyrics:

    > Bought me a cat and the cat pleased me,
    > I fed my cat under yonder tree.
    > Cat goes fiddle-i-fee.
    >
    > Bought me a hen and the hen pleased me,
    > I fed my hen under yonder tree.
    > Hen goes chimmy-chuck, chimmy-chuck,
    > Cat goes fiddle-i-fee.
    >
    > Bought me a duck and the duck pleased me,
    > I fed my duck under yonder tree.
    > Duck goes quack, quack,
    > Hen goes chimmy-chuck, chimmy-chuck,
    > Cat goes fiddle-i-fee.
    >
    > Bought me a goose and the goose pleased me,
    > I fed my goose under yonder tree.
    > Goose goes hissy, hissy,
    > Duck goes quack, quack,
    > Hen goes chimmy-chuck, chimmy-chuck,
    > Cat goes fiddle-i-fee.

    For example:

    ```python
    def bought(animal):
        print(f'Bought me a {animal} and the {animal} pleased me.')

    bought('cat')
    ```

## Submitting Your Work

1. Make sure the assignment repository is opened in VS Code.

2. Make sure you have completed all the tasks.

3. (First time only)
Use Command + J to open the Terminal tab and config your git username and email:
    ```bash
    git config user.name "Your Name"
    git config user.email "Your GitHub Email"
    ```

4. Click on the "Source Control" icon on the left. Source Control

    ![1](https://github.com/BlueinnoClassroom/404B-L2.1-Template/assets/155412668/2c31026e-c14d-484f-bb9e-dc87189a0216)

5. Enter a commit message and click on the "Commit" button.

Click on the "Sync Changes" button.

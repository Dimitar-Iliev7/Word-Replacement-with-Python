# Word Replacement with Python

In Python, the str.replace() method is used to replace a substring in a string with another substring. It takes two arguments:
1. The substring to be replaced.
1. The substring to replace the first substring.
___

For example, suppose we have a string called sentence and we want to replace all occurrences of the word "dog" with "cat".
We can do this using the replace() method as follows:

```python
sentence = "I have a dog. My dog is black."
new_sentence = sentence.replace("dog", "cat")
print(new_sentence)


```
Output: 

```python
I have a cat. My cat is black.

```

# Python Dictionaries Lab 📖 🐍

## Step 1 - Dictionaries
A dictionary (`dict`) is a way to store related data in Python using `key:value` pairs. One way to create a new dictionary is to use `{ }` with each set of `key:value` pairs seperated with a comma. Values can be any data type `str`, `int`, `list`, or even `dict`. We could store information about states and their capitals in a Python dictionary.

```python
states = {
  'Indiana': 'Indianapolis',
  'Kentucky': 'Frankfort',
  'Ohio': 'Columbus',
  'Michigan':'Lansing'
}
```
### Your Turn...
Create a new python dictionary to store data about your favorite automobile 🚙. Add keys for the `make`, `modle`, `color`, `cost`. Find an automobile you like and add values for each key. The `cost` value shoule be an `int`. Print out your dictionary using the `print( )` command

{% spoiler "Need help?" %}
If you name your dictionary `car`, then you can print the entire dictionary using
```python
print(car)
```
{% endspoiler %}

{% next "Step 2" %}

## Step 2 - Printing individual values
To print out the value for a given key you can use bracket notation. This is similar to how we print out an item in a list, the difference is instead of using the index number, we need to use the key. For example if you we wanted to see the capital of Ohio, we would use.
```python
print(states['Ohio'])
```
The result would be: 
```bash
Columbus
```
  

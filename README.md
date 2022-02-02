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
Create a new python dictionary to store data about your favorite automobile 🚙. Add keys for the `make`, `model`, `color`, `cost`. Find an automobile you like and add values for each key. The `cost` value shoule be an `int`. Print out your dictionary using the `print( )` command

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
### Your Turn...
Print out the `make` and `model` of your automobile using a single print statement. There are a few different ways you can do this. (You can use an f-string just be careful with ' and ")

{% spoiler "Need help?" %}
If you name your dictionary `car`, then you can print the entire dictionary using
```python
print(f"One of my favorite cars is the {car['make']} {car['model']}!")
# --> One of my favorite cars is the Ford Mustang!
```

{% endspoiler %}

{% next "Step 3" %}

## Step 3 - get() and update()
When you try to access or print out a key that is NOT in the dictionary, Python throws a `KeyError` and crashes. To keep this from happening we can use the `.get()` method. For example, if we try to print out the capital of Illinois using `print(state['Illinois'])` we would get a `KeyError` and our program woud crash. but if we try to print it out with `.get()`...
```python
print(state.get('Illinois'))
```
Nothing happens, actually `.get()` returns `None` if the key doesn't exist. 

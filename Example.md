# SimpleStore Example

## 1. Save a value

Use:

SaveValue
    name = "username"
    value = TextBox1.Text

Example:

username → Hasim

## 2. Get a value

Use:

GetValue
    name = "username"
    defaultValue = ""

The result is:

Hasim

## 3. Check a value

Use:

HasValue
    name = "username"

Result:

true / false

## 4. Delete a value

Use:

DeleteValue
    name = "username"

## 5. Memo list

Add a memo:

AddToList
    name = "memos"
    item = TextBoxMemo.Text

Get memos:

GetList
    name = "memos"

Remove a memo:

RemoveFromList
    name = "memos"
    item = TextBoxMemo.Text

Clear all memos:

ClearList
    name = "memos"

## 6. Persistent storage

Values remain available after closing and reopening the app.

## 7. Namespace

The default namespace is:

SimpleStoreData

Changing the namespace creates a separate local storage area.

# SimpleStore

SimpleStore is a local persistent storage extension for MIT App Inventor.

## Features

### Storage
- SaveValue — Save a value using a name/key.
- GetValue — Get a saved value.
- DeleteValue — Delete one saved value.
- HasValue — Check whether a key exists.
- ClearStore — Clear all stored data.
- GetAllData — Get all stored data as JSON.
- GetAllNames — Get all stored names/keys.

### Memo/List
- AddToList — Add an item to a list.
- GetList — Get a stored list.
- RemoveFromList — Remove an item from a list.
- ClearList — Clear one list.

### Events
- ValueSaved — Fires after a value is saved.
- ValueDeleted — Fires after a value is deleted.
- StoreCleared — Fires after all stored data is cleared.

### Namespace
Namespace allows different SimpleStore components to use separate local storage areas.

## Storage Type

SimpleStore stores data locally on the Android device.

It does not require an internet connection or a cloud server.

## Example

Save:

name = username
value = Hasim

Get:

name = username

Result:

Hasim

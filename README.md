# gson-preferences-storage
Simple library to persist typed objects and primitive values in SharedPreferences using Google Gson.


Usage:

```

  // Default Storage object, package-named SharedPreferences and Simple Gson
  Storage storage = Storage.create(context);

  // Default Storage object, SharedPreferences loaded from your name and Simple Gson
  Storage storage = Storage.create(context, "My Shared Preferences Name");

  // Default Storage object, SharedPreferences loaded from your name and Simple Gson
  Storage storage = Storage.create(sharedPreferencesInstance, gsonInstance);

  After initialization, you can use in your code calling:
  Storage storage = Storage.get();

  It's recommended to create the Storage object inside your application class, and use it as singleton inside the application.

```

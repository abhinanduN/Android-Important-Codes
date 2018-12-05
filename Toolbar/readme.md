```java
Toolbar toolbar1 =findViewById(R.id.toolbar_id);
setSupportActionBar(toolbar1);

ActionBar actionbar = getSupportActionBar();
actionbar.setDisplayHomeAsUpEnabled(true);
actionbar.setDisplayShowHomeEnabled(true);
actionbar.setTitle(R.string.title_apply_for_leave);
```
```java
@Override
public boolean onOptionsItemSelected(MenuItem item) {
  switch (item.getItemId()) {
      case android.R.id.home:
          finish();
          break;
  }
  return true;
}
    
```

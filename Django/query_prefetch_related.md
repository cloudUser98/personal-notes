# Query API prefecth_related()

```python
Model.objects.prefecth_related("lookup", ...)
```

Returns a QuerySet object with the selected relations already retrieved to improve data
accessing times.

Instead of adding the relations as joins in the Database query like select_related() it does the
lookups separately and create the "joins" in Python.

select_related() only works for direct relations and not Many2Many relations. prefetch_related()
does support Many2Many lookups.

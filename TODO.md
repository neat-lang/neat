blocking:
- interfaces
- generic namespaces
- dedicated bool type
- public, private?
- ranges?

pending:

- fold ClassMethodPtr into LateSymbol
- endLifetime should not take or need to take a Reference!
- copyInto should not exist; instead there should be a copy() op that can then be chained into Assignment.
    - Sure? Needs more thinky. Maybe just `beginLifetime`?

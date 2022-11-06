```python
class Null(Alive):

    description: str = "[ ]"

    alias: list[str] = ["nullqwertyuiop", "null"]

    ability: set[str] = set()

    maintaining: list[Repository] = [
        Repository(name="nullqwertyuiop/Eric", active=True),
        Repository(name="nullqwertyuiop/EricPlugins", active=True),
        Repository(name="nullqwertyuiop/EricPluginsTemplate", active=True),
    ]

    inactive: list[Repository] = [
        Repository(name="ProjectNu11/Project-Null", active=False),
        Repository(name="ProjectNu11/PN-Plugins", active=False),
        Repository(name="nullqwertyuiop/Chitung-python", active=False),
    ]

    collaborating: list[Repository] = [
        Repository(name="SAGIRI-kawaii/sagiri-bot", active=True),
    ]

    stable: Any = Ellipsis
```
